# dapp-election
2022

node v16.13.1
npm 8.1.2
truffle v5.0.2
solidity 0.5.0






Follow the steps below to download, install, and run this project.

Dependencies
they come with truffle unbox pet-shop

NPM: https://nodejs.org
Truffle: https://github.com/trufflesuite/truffle
Ganache: http://truffleframework.com/ganache/
Metamask: https://metamask.io/
Step 1. Clone the project
git clone https://https://github.com/collettshuma/dapp-election.git

Step 2. Install dependencies
$ cd election
$ npm install
Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 

Step 4. Compile & Deploy Election Smart Contract
$ truffle migrate --reset You must migrate the election smart contract each time your restart ganache.

Step 5. Configure Metamask


Unlock Metamask
Connect metamask to your local Etherum blockchain provided by Ganache.
Import an account provided by ganache.
Step 6. Run the Front End Application
$ npm run dev Visit this URL in your browser: http://http://http://localhost:3009/
