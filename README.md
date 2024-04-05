How to use Templates?
To use templates, follow the steps mentioned below:

1. Install the CW3D NPX package
In your terminal, navigate to the folder you want to create your project in and run:

Bash
npx create-web3-dapp@latest


If you've previously installed create-web3-dapp globally via npx create-web3-dapp:

The CLI builder will notify you if a new version has been released. In any case, we always suggest you to run using the latest available version by running npx create-web3-dapp@latest.

2. Insert a project name and starting project
You'll now get asked to insert a project name and a starting project to start from:

Create empty full-stack dapp: With is option you will be given an empty full-stack dapp with wallet connection built-in using Rainbow Kit, optionally, you can also choose to add a blockchain development environment (Hardhat or Foundry) in the project and adding a pre-defined smart contract like ERC721, ERC721A etc.
Create pre-built template: You can select a pre-built template for a dapp with this option. Right now we have the Block Explorer dapp as a template and we are actively working on adding more templates soon!
Choose the "Create pre-built template" option.

3. Select a template
Select the template that you want to start with. In this case, we are selecting the "NFT Explorer" template.

4. Choose your chain
Once you have selected your starting template, you'll need to choose the chain you want to configure your project for. Note that you can always modify or add more chains in the future. Current choices include:

Ethereum
Polygon
Arbitrum
Optimism

5. Select testnet or mainnet
Select if you want to configure with mainnet or testnet. We generally recommend starting with a testnet if you're not ready to deploy to the live chain yet. Here are the corresponding test networks for each chain:

Ethereum -> Goerli
Polygon -> Mumbai
Arbitrum -> Arb-Goerli
Optimism -> Opt-Goerli

6. Create an Alchemy Account or Enter your API key
Then you will be asked if you already have an Alchemy account, selecting yes or no based on if you have the Alchemy account or not.

