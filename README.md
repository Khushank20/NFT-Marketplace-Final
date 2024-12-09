# NFT Marketplace

An Ethereum-based decentralized application (DApp) for creating, buying, and selling Non-Fungible Tokens (NFTs) on the blockchain. The project is built using Solidity for smart contracts, React for the frontend, and Hardhat for contract development and testing.

---

## Features

- **Mint NFTs**: Create your unique tokens with custom metadata.
- **Buy and Sell NFTs**: Trade NFTs on the marketplace with listed prices.
- **Real-Time Data**: Fetch and display live NFT data using Web3.
- **Secure Transactions**: All transactions are managed securely on the blockchain.

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Technologies Used](#technologies-used)
5. [Environment Variables](#environment-variables)
6. [Contributing](#contributing)
7. [License](#license)

---

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v16 or later)
- [Hardhat](https://hardhat.org/)
- [Metamask](https://metamask.io/) (for interacting with the DApp)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/nft-marketplace.git
   cd nft-marketplace
   npm install
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network <network_name>
   npm start

## Usage
    Connecting Wallet: Open the application and connect your MetaMask wallet.
    Mint NFTs: Navigate to the "Mint" page, provide metadata, and mint a new token.
    Marketplace: View listed NFTs, buy, or list your NFTs for sale.
    Interact with Blockchain: Ensure you have test ETH or the required token for transactions.

## Project Structure
nft-marketplace/
├── contracts/       # Solidity smart contracts
├── scripts/         # Deployment scripts
├── src/             # Frontend source code
│   ├── components/  # React components
│   ├── pages/       # Page components
│   ├── utils/       # Utility functions for blockchain interaction
├── public/          # Public assets
├── artifacts/       # Generated artifacts from smart contracts
├── hardhat.config.js # Hardhat configuration
└── .env             # Environment variables (not included in version control)




