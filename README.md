```markdown
# zk-CrossVote: Unified Governance Across Chains

![zk-CrossVote Logo]()

Welcome to zk-CrossVote, a robust cross-chain governance management platform built on zkEVM. This innovative solution integrates Ethereum, Polygon zkEVM, Chainlink Automation, and Phala Network, aiming to streamline decentralized governance across multiple blockchain networks.

## Project Overview

zk-CrossVote addresses the challenges associated with dispersed governance across various blockchain networks. In many decentralized autonomous organizations (DAOs), token holders are often siloed, leading to uneven voting power distribution. Our platform introduces a cross-chain governance structure that aggregates voting power irrespective of token ownership. By integrating Ethereum and zkEVM, zk-CrossVote enables seamless, democratic participation and governance that accurately reflects the perspectives of all token holders.

- [GitHub Repository]()
- ![Flowchart 1](https://github.com/samarabdelhameed/pics/blob/main/BmbgDjl7vS.png)
- ![Flowchart 2](https://github.com/samarabdelhameed/pics/blob/main/Screen%20Shot%202024-03-18%20at%201.24.58%20PM.png)
- [Figma Design]()
- [YouTube Demo]()
- [Constellation: A Chainlink Hackathon won Polygon - LxLy Bridge zkEVM Extension]()

## Problem Statement

### Fragmented Governance Across Blockchain Networks

In decentralized organizations spanning multiple blockchain networks, governance is often decentralized and token holders may find themselves in isolated silos. This fragmentation leads to an unequal distribution of voting power, hindering the democratic governance process. Current solutions struggle to provide a unified governance structure that can seamlessly aggregate voting power across diverse blockchain ecosystems.

## Problem Challenges

1. **Token Holder Disparity:** Token holders across different chains lack a unified platform to exercise their governance rights, resulting in disparate voting power.
2. **Cross-Chain Governance Complexity:** Existing governance solutions do not effectively address the intricacies of decentralized governance across multiple blockchain networks.
3. **Inefficient Voting Representation:** Token ownership on one chain does not translate proportionately to voting power on other chains, causing a lack of accurate representation.

## Solution Overview

### zk-CrossVote - Unifying Cross-Chain Governance

#### Objective

zk-CrossVote aims to revolutionize decentralized governance by offering a comprehensive cross-chain governance management platform. It addresses the challenges of fragmented governance by introducing a unified framework that aggregates voting power regardless of token ownership across various blockchain networks.

#### Key Features and Solutions

1. **Encouraging Decentralized Management:**
   - zk-CrossVote enables DAO members to seamlessly incorporate their token holdings on Ethereum mainnet and Polygon zkEVM networks.
   - The LXLY bridge aligns token balances between chains, ensuring fair representation of voting power.

2. **Simplified DAO Administration:**
   - The GovXWrapper, integrated with OpenZeppelin's governance contracts, streamlines the governance process.
   - Automation features from Phala Network and Chainlink ensure precision and promptness in governance actions.

3. **Integrated Method for Decentralized Decision-Making:**
   - zk-CrossVote provides a user-friendly interface, inviting users to actively engage in the democratic process.
   - Every decision is significant, every interaction is intuitive, and every member has a voice in the platform's meticulously crafted environment.

#### Outcomes

- Unified governance structure across blockchain networks.
- Fair representation of voting power for all token holders.
- Streamlined and automated governance processes.

## Technologies Utilized

### Chainlink Automation

Chainlink time-based triggers execute claim functions every hour, ensuring timely and accurate governance actions.

- [UpKeep Link](https://automation.chain.link/goerli/56209270301599875549343820271679309979009473186668399424303531307152837514484)
- [Transaction Details](https://goerli.etherscan.io/address/0x05222e5f67d4a4b363ca65ed7fcd25c3353e1972#internaltx)

### Phala Network

For message claiming, zk-CrossVote leverages specific Merkle proofs related to source transactions. Phala Network integration facilitates efficient message claiming processes.

- [Code](https://github.com/samar19/zkChainUnity/blob/main/AutoClaimPhat/src/index.ts)
- [Transaction Details](https://goerli.etherscan.io/tx/0xdd8288c2cc98f5ab073bb8079249e1b2bf30727ccc29c5fc405da0526bdb531b)

### Polygon ZkEVM

The VoteOnZkEVM contract is deployed on the Polygon ZkEVM Testnet, extending governance capabilities to the Polygon network.

- [VoteOnZkEVM Contract Details](https://testnet-zkevm.polygonscan.com/address/0x611bb13B02D8FD1E94762b976cAC1fb01Ae39111)

### Goerli

On the Goerli network, zk-CrossVote deploys the GovXWrapper contract, facilitating cross-chain governance.

- [GovXWrapper Contract Details](https://goerli.etherscan.io/address/0x9A5d0A5aD88C00308C53aA0b692Af33edAe7d895)
- [Autoclaim Contract Details](https://goerli.etherscan.io/address/0x05222e5f67d4a4b363ca65ed7fcd25c3353e1972)

## Installation

To run the zk-CrossVote project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone 
    cd zk-CrossVote
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Deploy Contracts**:
    - Follow the instructions in the `deploy` folder to deploy the necessary smart contracts on Goerli and Polygon zkEVM testnets.

4. **Run the application**:
    ```bash
    npm start
    ```

## Usage

To use the zk-CrossVote platform:

1. **Register your DAO**: Create a governance contract on Ethereum.
2. **Create Proposals**: Submit proposals for governance on Ethereum.
3. **Vote on Proposals**: Cast votes on proposals via the zkEVM network.
4. **Automated Processes**: Rely on automated systems to claim messages and tally votes accurately.

## Flowchart

Below is the flowchart for the project:



## Demo

Check out our [live demo]() to see zk-CrossVote in action.

## Figma UI

Explore our user interface designs on [Figma]().

## Contributing

We welcome contributions to the zk-CrossVote project. To contribute:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make your changes** and commit them:
    ```bash
    git commit -m "Add your commit message"
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Chainlink](https://chain.link/)
- [Phala Network](https://phala.network/)
- [Polygon](https://polygon.technology/)
- [OpenZeppelin](https://openzeppelin.com/)

