# Simple DAO App

This is a simple decentralized autonomous organization (DAO) app built on the Internet Computer platform using Motoko.

## Introduction

This DAO app allows users to create and vote on proposals using tokens. It maintains accounts, proposals, and system parameters. Users can transfer tokens, create proposals, and vote on existing proposals.

## Features

- Account management: Users can create accounts and transfer tokens.
- Proposal creation: Users can create proposals with specified actions.
- Voting: Users can vote on proposals to accept or reject them.
- System parameters: Transfer fee, proposal vote threshold, and proposal submission deposit can be updated.

## Installation and Deployment

To run this app locally, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have the DFINITY Canister SDK (DFX) installed.
3. Start the Internet Computer replica by running the following command:

```bash
dfx start --background
```

4. Deploy the canisters to the replica and generate the Candid interface by running:

```bash
dfx deploy
```

5. Once deployed, you can interact with the app using its generated interface.
