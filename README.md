# Nepoymupochemunet
Zdes ya eshe raz budu chtoto pisat, potomu chto v perviy raz ne poluchilos 
# Simple Solidity Smart Contract: HelloEthereum

This project contains a basic Ethereum smart contract written in Solidity. The contract demonstrates the structure of a simple greeting storage system.

## 📜 Contract Overview

The `HelloEthereum` contract allows you to:

- Set a custom greeting message
- Read the current greeting

Perfect for learning Solidity basics or testing out smart contract interactions.


## 🔧 How It Works

1. Deploy the contract to a testnet or local blockchain.
2. Call `setGreeting()` to update the greeting.
3. Use `getGreeting()` to read the stored greeting message.

## 💡 Example

```solidity
HelloEthereum greeter = new HelloEthereum();
greeter.setGreeting("Hello, Web3!");
string memory message = greeter.getGreeting(); // Returns "Hello, Web3!"
