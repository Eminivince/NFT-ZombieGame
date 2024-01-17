# NFT Zombie Game

Welcome to the **NFT Zombie Game**, a unique blockchain-based project that showcases the fascinating use of Non-Fungible Tokens (NFTs) in the gaming world. PS: This is the outcome of my project on CryptoZombies(LOOM) This project, built using Hardhat, demonstrates the integration of smart contracts, NFTs, and interactive gaming elements.

## Game Overview

In the NFT Zombie Game, players have the opportunity to create and interact with their own unique zombie characters. Each zombie possesses distinct DNA, generated through a novel naming mechanism. This DNA influences the appearance and attributes of the zombie, ensuring that each character is one-of-a-kind.

### Note that the deploy script for this project has not been written to deploy the contracts yet as I focused mainly on the solidity aspect. You may want to write a script for deployment.
### Key Features

- **Zombie Generation:** Create unique zombies with specific DNA based on the name you choose for them.
- **Feeding Mechanism:** Zombies can feed to gain strength and potentially unlock new abilities or features.
- **Combat System:** Engage in battles with other zombies, showcasing a strategic combat system that leverages the unique attributes of your zombie.
- **Leveling Up:** As your zombie engages in various activities, they gain experience and level up, unlocking new capabilities and enhancements.

## Getting Started

To get started with this project, you'll need to have Node.js installed on your machine. After cloning the repository, you can run the following commands to explore various aspects of the project:

```shell
npx hardhat help            # Displays help and available Hardhat tasks
npx hardhat test            # Run tests for the smart contract
REPORT_GAS=true npx hardhat test   # Run tests with gas usage report
npx hardhat node            # Start a local Ethereum node

*npx hardhat run scripts/deploy.js  # Deploy the contract to the local node*

