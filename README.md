# FT-Blockchain-Project
# DTEXAuction

DTEXAuction is a decentralized application (DApp) that implements Dutch auctions for ERC-721 tokens and handles ERC-20 token interactions. The smart contract allows users to mint NFTs (Non-Fungible Tokens), start auctions, place bids using USDT (ERC-20), and end auctions.

## Table of Contents

- [DTEXAuction](#dtexauction)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
    - [1. Clone the repository](#1-clone-the-repository)
    - [2. Install Dependencies](#2-install-dependencies)
    - [3. Compile the Smart Contract](#3-compile-the-smart-contract)
    - [4. Deploy the Smart Contract](#4-deploy-the-smart-contract)
  - [Usage](#usage)
    - [Minting and Starting an Auction](#minting-and-starting-an-auction)
    - [Placing a Bid](#placing-a-bid)
    - [Ending an Auction](#ending-an-auction)
  - [Frontend Integration](#frontend-integration)
  - [Events](#events)
  - [License](#license)

## Project Description

This project provides a complete implementation of a Dutch auction system for NFTs using Solidity. The smart contract manages auction lifecycles, including minting new tokens, starting auctions, placing bids, and ending auctions. The frontend allows users to interact with the smart contract via MetaMask.

## Prerequisites

- Node.js
- npm (Node Package Manager)
- Truffle
- Ganache or any Ethereum test network
- MetaMask
- Solidity ^0.8.0

## Setup

**### 1. Clone the repository**

sh
git clone https://github.com/yourusername/DTEXAuction.git
cd DTEXAuction

**### 2. Install Dependencies**

sh

npm install

**### 3. Compile the Smart Contract**

sh

truffle compile

**### 4. Deploy the Smart Contract**

Update the truffle-config.js file with network configuration and deploy the contract:

sh

truffle migrate --network <network_name>
