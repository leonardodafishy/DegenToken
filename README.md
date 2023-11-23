# DegenToken Smart Contract

The DegenToken smart contract is an Ethereum-based ERC-20 token contract designed to offer enhanced functionalities beyond the standard features. It facilitates token minting, burning, power-up purchases, balance checks, and seamless token transfers between addresses.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Introduction

The DegenToken smart contract is a versatile solution tailored for diverse use cases, serving as a foundational framework for managing tokens and digital assets, especially within gaming ecosystems.

## Features

### 1. Minting
- The contract owner enjoys the privilege of minting new tokens and distributing them to specified addresses, effectively expanding the total token supply.

### 2. Burning
- Token holders have the autonomy to burn (eliminate) their own tokens, diminishing their personal token balance and contributing to overall token supply management.

### 3. Power-Ups
- Introducing a distinctive feature called "Power-Ups," users can acquire these enhancements by spending Degen tokens. Each power-up is characterized by a name, price, and duration, providing in-game advantages. The process of obtaining power-ups is termed "redeeming."

### 4. Balance Checks
- The contract incorporates robust balance checks to ensure users possess sufficient tokens before executing actions such as token transfers or power-up purchases.

### 5. Token Transfers
- Users can effortlessly transfer Degen tokens to other Ethereum addresses using the "transferTokens" function, granted they hold a balance exceeding the specified amount.

## Getting Started

To deploy and engage with the DegenToken smart contract, a foundational understanding of Ethereum development and the Solidity programming language is essential. Deployment can occur on either a development or mainnet Ethereum network.

## Usage

1. Deploy the contract on an Ethereum network.
2. If the contract owner, mint tokens to increase the token supply.
3. Utilize the "transferTokens" function for seamless token transfers.
4. Burn tokens when necessary to manage the token supply.
5. Enrich user experiences by adding custom power-ups via the "addCustomPowerUp" function.
6. Users can then acquire power-ups using the "purchasePowerUp" function.
7. Verify user power-ups and their remaining durations through dedicated functions.

## Author
Authored by Miguel Angelo M. Fesalbon

## License
This smart contract is released under the MIT License.
