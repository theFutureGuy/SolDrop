# SolDrop

This project is a simple demonstration of how to perform a Solana airdrop from one account to another using web3.js, React, and the Phantom wallet.

## Overview

The demo includes a basic React frontend that interacts with the Solana blockchain through the web3.js library. It utilizes the Phantom wallet for authentication and transaction signing.

## Prerequisites

Before running the demo, ensure you have the following installed:

- Node.js and npm
- React
- Phantom wallet extension (for testing on the Solana devnet)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/solana-airdrop-demo.git
    ```

2. Navigate to the project directory:

    ```bash
    cd solana-airdrop-demo
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Configuration

1. Open the `src/config.js` file and update the following variables:

   - `sourcePrivateKey`: Private key of the source account from which the airdrop will be initiated.
   - `destinationPublicKey`: Public key of the destination account to receive the airdrop.

## Run the Demo

1. Start the React development server:

    ```bash
    npm start
    ```

2. Open your browser and go to [http://localhost:3000](http://localhost:3000).

3. Connect your Phantom wallet to the demo by clicking the "Connect Wallet" button.

4. Click the "Airdrop" button to initiate the airdrop from the source account to the destination account.

## Important Note

This demo is intended for educational purposes and uses the Solana devnet. Do not use real SOL tokens or private keys on the devnet.

## Resources

- [Solana Documentation](https://docs.solana.com/)
- [web3.js Documentation](https://web3js.readthedocs.io/)
- [React Documentation](https://reactjs.org/)
- [Phantom Wallet](https://phantom.app/)

## Acknowledgements

This project was created by Ashiq as a part of the Solana development community.

