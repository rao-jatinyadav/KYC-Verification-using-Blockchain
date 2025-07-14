# KYC-Verification-using-Blockchain
Creating a KYC verification using Solidity Blockchain
Is a project based on blockchain of KYC registry using local test net and Solidity using various modules like Ganche-cli, Nodejs, NPM, SOLC, HTML, CSS, etc.

# Project Description
Know Your Customer (KYC) processes are critical for financial institutions but are often cumbersome, costly, and prone to inefficiencies. The KYC-chain project seeks to revolutionize this area by leveraging blockchain technology to create a streamlined and secure KYC registry.
KYC-chain eliminates the need for redundant KYC checks by maintaining a unified and tamper-proof database on a blockchain. This approach not only reduces costs for banks but also enhances data security and integrity.

# Key Features
Blockchain-based Registry: Utilizes blockchain's immutable ledger to store KYC information securely.
Elimination of Redundancies: Reduces duplicate KYC checks, saving time and resources.
Proof-of-Reputation: Enhances verification processes by establishing reputation-based trust mechanisms.
Scalability: Future plans include deployment on the Ethereum network for increased scalability and accessibility.

# System Requirements
=>Software
Node.js - v10.15.3 or higher
npm - v6.9.0 or higher
solc - v0.4.26 (npm install solc@0.4.26)
web3 - v0.20.1 (npm install web3@0.20.1)
ganache-cli - v6.4.3

=>Hardware
-> Operating System:
Windows 10 or later
macOS 10 or later
-> Processor:
Intel Core i5 11th generation or above
AMD Ryzen 5 or above
-> Graphics Card:
Intel Iris XE or better

# Instructions to Run
Follow these steps to run KYC-chain on your local environment:

1. Open a terminal window and start the Ganache CLI with the command ganache-cli.
2. Open another terminal window and navigate to the project's root directory.
3. Execute the initialization script init.js using Node.js: node init.js.
4. After a few seconds, you will receive a 20-byte address, which represents the compiled smart contract's  address.
5. Edit the contractDetails.js file located in root\js\contractDetails.js using a text editor.
6. Update the contract instance address (variable contractAddress) with the address obtained in step 4.
7. Ensure that Ganache CLI is running as it acts as the local Ethereum test network.
8. You can now use the KYC-chain application.

# Future Enhancements
In the future, we plan to:

1. Deploy the registry on the Ethereum network for improved scalability.
2. Implement additional features such as user access controls.
3. Make UI more intuative.
4. Make it avaiable for more Secure Channels/accounts.
5. Make the Secure Channels/accounts tranction currency in our case ETH rechargeable.

# Made By
Name: Jatin Yadav
Class: CE 41
Roll Number: 22001003056
