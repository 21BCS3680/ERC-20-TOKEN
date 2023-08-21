# Degen Gaming Token Smart Contract
This repository contains the Solidity smart contract for the Degen Gaming Token, an ERC20 token deployed on the Avalanche network. The smart contract implements features that allow players to redeem tokens for in-game items in the Degen Gaming ecosystem.

# Table of Contents
Overview
Features
Requirements
Getting Started
Usage
Contract Details
Contributing

# Overview
The Degen Gaming Token smart contract provides an example of how to create an ERC20 token on the Avalanche network with additional functionalities for players to redeem tokens for in-game items. The contract includes the ability to mint tokens, transfer tokens, redeem tokens, check token balances, and burn tokens.

# Features
Minting new tokens by the contract owner.
Transferring tokens between players.
Redeeming tokens for in-game items from the store.
Checking token balance for players.
Burning tokens that are no longer needed.
# Requirements
Remix or Truffle for deploying the contract.
Connection to the Avalanche network.
Basic understanding of Solidity smart contract development.
# Getting Started
Clone this repository to your local machine.
Open the contract file (DegenGamingToken.sol) in Remix or Truffle.
Compile and deploy the contract to the Avalanche network using Remix or Truffle.
# Usage
Deploy the contract to the Avalanche network.
Use the owner's account to mint tokens.
Players can transfer tokens to each other using the transfer function.
Players can redeem tokens for in-game items using the redeem function (implement in-game logic here).
Players can check their token balance using the balanceOf function.
Anyone can burn their own tokens using the burn function.
# Contract Details
DegenGamingToken.sol: The main smart contract implementing the Degen Gaming Token functionality.
Ownable.sol: Imported from OpenZeppelin to provide access control for the contract owner.
ERC20.sol: Imported from OpenZeppelin to provide standard ERC20 token functionality.
# Contributing
Contributions to this project are welcome! Feel free to fork the repository and submit pull requests with any improvements or bug fixes.
