# ChatDApp Contract

## Description
The ChatDApp contract allows users to send messages and view chat history. It is designed to be used in conjunction with the Ethereum Name Service (ENS) for user authentication. 
The App also includes a gasless transaction mechanism.

## Deployment Addresses: 
Chat C/A 0x23446d7Fa9aAf8cFD29cE0BF550f199F8FbeC4f8
ENS C/A 0x131170a067C820F8Ae8feB4A9294C5138bBeA88c
System Storage C/A 0x6b736ce86e9F9f551E4CA336568203f51Ea380fA

## Features
- Users can send messages.
- Users can view their chat history.
- Users can upload profile images, which are uploaded on IPFS. 

## Usage
1. Deploy the ChatDApp contract to the Ethereum blockchain.
2. Set the address of the ENS contract using the constructor.
3. Use the `sendMessage` function to send messages.
4. Use the `getChatHistory` function to view chat history.

## Installation
To use the ChatDApp contract, follow these steps:
1. Clone the repository.
2. Install dependencies if any.
3. Deploy the ChatDApp contract to the Ethereum blockchain.
4. Set the address of the ENS contract using the constructor.

## Contract Details
- Solidity Version: ^0.8.19
- License: MIT
- SPDX License Identifier: MIT
- ENS Interface: IENS.sol

## Dependencies
- IENS.sol: Interface for the Ethereum Name Service (ENS) contract.
