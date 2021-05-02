## About
This is a project of Udacity Nano degree blockchain programme. 
The smart contract registers a star as NFT on Rinkeby test network.

##Run the application

###Clean the frontend

`cd app`

###1. Remove the node_modules

remove packages

`rm -rf node_modules`

clean cache

`npm cache clean`

`rm package-lock.json`

initialize npm (you can accept defaults)

`npm init`

install all modules listed as dependencies in package.json

`npm install`

###2. Start Truffle by running
For starting the development console

`truffle develop`

Enters the truffle development console.
For compiling the contract, inside the development console, run:

`compile`

For migrating the contract to the locally running Ethereum network, inside the 
development console

`migrate --reset`

For running unit tests the contract, inside the development console, run:

`test`

###3. Frontend
Once you are ready to start your frontend, run the following from the app folder in a new terminal:

`cd app`
`npm run dev`


## Connection to Rinkeby Test Network
Be sure that MetaMask is connected to Rinkeby test network, and the account has funds. 
You may get some free fund via https://faucet.rinkeby.io/

``truffle migrate --network rinkeby``

## Note to the Instructor

Truffle v5.2.5

Openzeppelin 2.1.2

ERC-721 Token Name: Estrella

ERC-721 Token Symbol: EST

“Token Address” on the Rinkeby Network: 0x016e887f354ece52045367016ca99cad57953900
