# zkChainUnity

Welcome to zkChainUnity, a robust cross-chain governance management platform built on ZkEVM. This innovative solution , Chainlink Automation, and Phala Network, aiming to streamline decentralized governance across multiple blockchain networks.

## Project Overview

zkChainUnity addresses the challenges associated with dispersed governance across various blockchain networks. In many decentralized autonomous organizations (DAOs), token holders are often siloed, leading to uneven voting power distribution. Our platform introduces a cross-chain governance structure that aggregates voting power irrespective of token ownership. By integrating Ethereum and zkEVM, zkChainUnity enables seamless, democratic participation and governance that accurately reflects the perspectives of all token holders.
- [github link](https://github.com/samarabdelhameed/zk-ChainUnity)
- ![flow chart](https://github.com/samarabdelhameed/pics/blob/main/BmbgDjl7vS.png)
- ![flow chart](https://github.com/samarabdelhameed/pics/blob/main/Screen%20Shot%202024-03-18%20at%201.24.58%20PM.png)
 - [Figma link](https://www.figma.com/file/m2KyreOutNgftJC7zM0b7y/Untitled?type=design&node-id=0%3A1&mode=design&t=EKhB2uQ6EKnjAI9R-1)
 - [yotube link](https://www.youtube.com/watch?v=65Z969TesnQ)
  - [Constellation: A Chainlink Hackathon won Polygon - LxLy Bridge zkEVM Extension](https://devpost.com/software/zkchainunity)

 

## Problem Statement

**Fragmented Governance Across Blockchain Networks**

In decentralized organizations spanning multiple blockchain networks, governance is often decentralized and token holders may find themselves in isolated silos. This fragmentation leads to an unequal distribution of voting power, hindering the democratic governance process. Current solutions struggle to provide a unified governance structure that can seamlessly aggregate voting power across diverse blockchain ecosystems.

## Problem Challenges:

1. **Token Holder Disparity:** Token holders across different chains lack a unified platform to exercise their governance rights, resulting in disparate voting power.

2. **Cross-Chain Governance Complexity:** Existing governance solutions do not effectively address the intricacies of decentralized governance across multiple blockchain networks.

3. **Inefficient Voting Representation:** Token ownership on one chain does not translate proportionately to voting power on other chains, causing a lack of accurate representation.

## Solution Overview

**zkChainUnity - Unifying Cross-Chain Governance**

**Objective:**
zkChainUnity aims to revolutionize decentralized governance by offering a comprehensive cross-chain governance management platform. It addresses the challenges of fragmented governance by introducing a unified framework that aggregates voting power regardless of token ownership across various blockchain networks.

**Key Features and Solutions:**

1. **Encouraging Decentralized Management:**
   - zkChainUnity enables DAO members to seamlessly incorporate their token holdings on Ethereum mainnet and Polygon zkEVM networks.
   - The LXLY bridge aligns token balances between chains, ensuring fair representation of voting power.

2. **Simplified DAO Administration:**
   - The GovXWrapper, integrated with OpenZeppelin's governance contracts, streamlines the governance process.
   - Automation features from Phala Network and Chainlink ensure precision and promptness in governance actions.

3. **Integrated Method for Decentralized Decision-Making:**
   - zkChainUnity provides a user-friendly interface, inviting users to actively engage in the democratic process.
   - Every decision is significant, every interaction is intuitive, and every member has a voice in the platform's meticulously crafted environment.

**Outcomes:**
- Unified governance structure across blockchain networks.
- Fair representation of voting power for all token holders.
- Streamlined and automated governance processes.

## Technologies Utilized

### Chainlink Automation

Chainlink time-based triggers execute claim functions every hour, ensuring timely and accurate governance actions.

- [UpKeep link](https://automation.chain.link/goerli/56209270301599875549343820271679309979009473186668399424303531307152837514484)
- [Transaction details](https://goerli.etherscan.io/address/0x05222e5f67d4a4b363ca65ed7fcd25c3353e1972#internaltx)

### Phala Network

For message claiming, zkChainUnity leverages specific Merkle proofs related to source transactions. Phala Network integration facilitates efficient message claiming processes.

- [Code](https://github.com/samar19/zkChainUnity/blob/main/AutoClaimPhat/src/index.ts)
- [Transaction details](https://goerli.etherscan.io/tx/0xdd8288c2cc98f5ab073bb8079249e1b2bf30727ccc29c5fc405da0526bdb531b)

### Polygon ZkEVM

The VoteOnZkEVM contract is deployed on the Polygon ZkEVM Testnet, extending governance capabilities to the Polygon network.

- [VoteOnZkEVM Contract details](https://testnet-zkevm.polygonscan.com/address/0x611bb13B02D8FD1E94762b976cAC1fb01Ae39111)

### Goerli

On the Goerli network, zkChainUnity deploys the GovXWrapper contract, facilitating cross-chain governance.

- [GovXWrapper Contract details](https://goerli.etherscan.io/address/0x9A5d0A5aD88C00308C53aA0b692Af33edAe7d895)
- [Autoclaim Contract details](https://goerli.etherscan.io/address/0x05222e5f67d4a4b363ca65ed7fcd25c3353e1972)


