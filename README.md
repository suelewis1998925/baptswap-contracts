
# Baptswap Contracts

## Overview

Baptswap Contracts is a decentralized exchange (DEX) smart contract system built on the Aptos blockchain. It enables secure and efficient token swaps, liquidity provision, and decentralized trading. The contracts are designed to be scalable, secure, and optimized for the Aptos Move ecosystem.

## Features

-   **Token Swaps**: Swap assets seamlessly with minimal fees.
    
-   **Liquidity Pools**: Provide liquidity to earn transaction fees.
    
-   **Move-based Security**: Built with Aptos Move to ensure safety and reliability.
    
-   **Low Latency**: Fast transactions leveraging Aptos' high-performance architecture.
    
-   **Scalability**: Designed for efficiency and future expansion.
    

## Requirements

To deploy and interact with the Baptswap contracts, ensure you have the following:

-   Aptos CLI
    
-   Move CLI
    
-   Rust and Cargo installed
    
-   Aptos testnet/mainnet account
    

## Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/suelewis1998925/baptswap-contracts.git
    cd baptswap-contracts
    ```
    
2.  Install dependencies:
    
    ```
    aptos move compile
    ```
    
3.  Run tests:
    
    ```
    aptos move test
    ```
    

## Deployment

1.  Configure your Aptos account:
    
    ```
    aptos init
    ```
    
2.  Publish the contracts:
    
    ```
    aptos move publish --profile default
    ```
    

## Usage

After deployment, you can interact with the contracts via the Aptos CLI, SDKs, or directly using blockchain explorers.

### Swap Tokens

Use the DEX interface or CLI commands to swap tokens.

### Provide Liquidity

Deposit assets into liquidity pools and earn fees.

## Contribution

We welcome contributions! Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.
