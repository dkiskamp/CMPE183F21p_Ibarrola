# CMPE 183 Final Project - NFT Marketplace

Before running ensure Node JS is installed on your system and that Metamask is installed on your browser. To deploy the application open two terminals in the base directory of the project.

#### Terminal 1:

To install dependencies run:

`npm install`

Afterwards run:

`npx hardhat node`

This will generate 20 accounts that have 10,000 ETH on a local test network.

#### Terminal 2:

To deploy the contracts run:

`npx hardhat run scripts/deploy.js --network localhost`

Then to run the server run:

`npm run dev`

If you did everything correctly the application should be deployed on a local server! Go to the following address to connect to the server:

`localhost:3000`



### Adding Wallets to Metamask

First ensure test networks are shown by going to 

`Settings > Advanced > Show Test Networks`

Afterwards switch to the localhost network by going to

`Network > Localhost 8545`

To import wallets click on the button in the top right and go to "Import Account", then paste the full private key into the field and click import. This should show a new account that has 10,000 ETH on the localhost network. Repeat this process as many times as desired. Now you can fully use the application! The first time using it Metamask will ask you to connect accounts. Just select all the accounts you want to use and click connect.
