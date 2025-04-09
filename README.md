# FoundIT
A smart contract that helps users get their lost items (work in progress)

# Lost & Found dApp (Polygon Network)

A decentralized application that helps users report and recover lost items through community collaboration and smart contract incentives on the Polygon (Ethereum Layer 2) blockchain.

## Overview

This dApp allows users to:
- Report lost items with description and optional image hash
- Set a reward in crypto (e.g. USDT, MATIC) for recovery
- Enable finders to submit claims with proof
- Automatically verify and release rewards via smart contracts

## Tech Stack

- **Blockchain:** Ethereum (Polygon Network)
- **Smart Contracts:** Solidity
- **Frontend:** React (Planned)
- **Storage:** IPFS (for item images or proofs)
- **Wallets:** MetaMask integration

## Features

- Decentralized item reporting and tracking
- Smart contract-based reward system
- Community participation for recovery
- Transparent and secure transactions

## Smart Contract Functions (Planned)

- `reportLostItem(string memory description, string memory ipfsHash)`
- `submitClaim(uint itemId, string memory proof)`
- `verifyClaim(uint claimId)`
- `releaseReward(uint claimId)`

## Live Demo (Coming Soon)

## Setup (Coming Soon)

Will include:
- Hardhat development environment
- Smart contract deployment to Polygon Mumbai/Testnet
- Frontend installation guide

## License

This project is licensed under the MIT License.
property of Floki, not to be used without consent

---

**Developed by:** Igbinoba Erere  
**Contact:** seekang82@gmail.com
