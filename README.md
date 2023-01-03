# Sample CIS2 Contracts

Concordium is a science-based proof-of-stake blockchain created for all, with in particular business applications in mind. [Read more about concordium](https://www.concordium.com/about)

This repository provides sample implementations of following ways in which a developer can interact with an on chain contract on Concordium.

- Using [Node SDK](https://www.npmjs.com/package/@concordium/node-sdk)

## Get Started

Throughout this repository [Concordium Testnet](https://testnet.ccdscan.io/) is being used to demo the functionality.

- Perquisites

  - Download and [Install Docker Compose](https://docs.docker.com/compose/install/)
  - [Install tools for Smart Contract development](https://developer.concordium.software/en/mainnet/smart-contracts/guides/setup-tools.html#setup-tools)
  - Clone this Repository
  - Create Concordium Account & Wallet
    - Download concordium testnet wallet
      - [For IOS, IPhone](https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#ios)
      - [For Android](https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#android)
    - [Create Testnet Account](https://developer.concordium.software/en/mainnet/net/guides/create-account.html)
    - [Export wallet](https://developer.concordium.software/en/mainnet/net/guides/export-import.html#export-import) and then copy the file in root named [concordium-backup.concordiumwallet](./concordium-backup.concordiumwallet)

- [Build Contracts](./concordium-contracts/README.md)

- Interact with Contracts
  - Using [Node SDK](./node-cli/README.md)
