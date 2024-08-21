## Avalanche_Subnet

# DeFi Empire: A Simple DeFi Kingdom Clone
This project is part of the Avax Advanced Module by Metacrafters, where you’ll create a basic DeFi Kingdom-style game on the Avalanche network.

# Steps to Build Your DeFi Kingdom Clone
1. Set Up Your EVM Subnet:

* Use the Avalanche CLI (only available on macOS and Linux) to create a custom EVM subnet on the Avalanche network.

* Windows users can install WSL (Windows Subsystem for Linux) to get Ubuntu and then follow the instructions.
2. Define Your Native Currency:
* Set up your in-game currency for the DeFi Kingdom clone.
3. Connect to MetaMask:

* Link your EVM Subnet to MetaMask by following the instructions provided.
4. Deploy Basic Game Components:

* Use Solidity and Remix to create and deploy the basic elements of your game, such as smart contracts for battling, exploring, and trading.
Color Guessing Game with Token Rewards
* This project also includes a simple number guessing game on the Avalanche EVM subnet. Here’s how it works:

Game Setup: Players guess a number between 1 and 10. If they guess correctly, they earn 5 tokens. If they run out of attempts without guessing the correct number, they lose tokens as a penalty.

# Creating Your Own EVM Subnet on Avalanche

1. Install Avalanche CLI: Follow the official documentation to install the Avalanche CLI on your machine.
* Windows Users: Use WSL to install Ubuntu.
2.Create a Subnet:
* Run avalanche subnet create mySubnet in your terminal to create a new subnet.
* Choose the SubnetEVM option for an EVM Subnet.
* Define your chain ID and token symbol.
3. Deploy the Subnet:
* Deploy your subnet using the command avalanche subnet deploy mySubnet.
* The console will display all the details about your new subnet.
4. Connect to MetaMask:
* Use the connection details from the Avalanche CLI to add your subnet to MetaMask.

# Contracts Overview
* GameToken.sol: Defines an ERC-20-like token called "The NumWarrior" (TNWR). It includes minting and transferring functions.
* NumberGuessingGame.sol: Implements the logic for the number guessing game and interacts with GameToken.sol.

# How to Use

1. Deploy Contracts:
* Deploy GameToken.sol first to get the token address.
* Deploy NumberGuessingGame.sol using the token address.
2. Play the Game:

* Players guess the secret number using the guessNumber function.
* The admin can generate a new secret number or reset attempts.

# Requirements
*  Solidity ^0.8.17
* Truffle or Remix for deployment and testing
* MetaMask or similar wallet for interaction

# Author
Khushi Ranjana

# License
This project is licensed under the MIT License.

