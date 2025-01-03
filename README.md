# SOLIDITY - Project: Ticket Booking System on Ethereum Blockchain

## Description
This project implements a ticket booking system using Ethereum smart contracts and NFTs. It allows users to purchase event tickets via Ether using a decentralized application (dApp). The tickets are minted as NFTs, and users can interact with the blockchain directly through MetaMask.

## Features
- Create events with details such as name, date, price, and available tickets.
- Users can purchase tickets, which are minted as NFTs.
- Admin can withdraw Ether from the contract.

## Tech Stack
- **Frontend**: ReactJS, MetaMask
- **Blockchain**: Solidity (Ethereum Smart Contracts)
- **Backend**: Hardhat (for local testing of Ethereum contracts)

## Installation

### Prerequisites
- Node.js (version >= 16)
- npm (Node package manager)
- MetaMask browser extension
- Hardhat (for smart contract testing)

### Setup

1. Clone the repository:
   ```bash
   https://github.com/rohith0224/TicketManager.git
2. Install dependencies:
    ```npm install```
3. Start a local Ethereum network using Hardhat:
    ```npx hardhat node```
4. In another terminal window, deploy the contracts:
    ```npx hardhat run scripts/deploy.js --network localhost```
5. Run the React app:
    ```npm start```
6. Open MetaMask, connect to the local network, and interact with the application.
