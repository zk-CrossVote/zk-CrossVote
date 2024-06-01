```markdown
# zk-CrossVote: Unified Governance Across Chains

![zk-CrossVote Logo](https://github.com/samarabdelhameed/pics/blob/main/Black%20Typographic%20Graphic%20Designer%20Logo.png)

## Project Overview

### Problem We Are Solving

The difficulty of dispersed governance across blockchain networks is what our project aims to solve. Token holders are frequently divided into silos and have a disproportionate amount of voting power when DAOs spread across several networks. Our platform offers a cross-chain governance structure that aggregates voting power regardless of token ownership, in an effort to unify this fragmented ecosystem. We ensure that no vote is overlooked in the multi-chain future by integrating Ethereum and zkEVM to enable smooth, democratic participation and governance that accurately reflects the views of all token holders.

### Encouraging Decentralized Management in All Chains

Our initiative is a shining example of innovation in the field of decentralized autonomy, providing a strong, unified cross-chain governance framework that is both inclusive and potent. This innovative solution aims to allow DAO members to incorporate their token holdings on the *Ethereum mainnet* and *Polygon zkEVM* networks, as well as to start and participate in governance initiatives on Ethereum. The key component of this system is the smooth integration offered by the *LXLY bridge*, which aligns token balances between chains to guarantee that each member's voting power is fairly represented and that the fundamentals of democratic participation are maintained.

### Simplified DAO Administration and Proposal Fulfillment

The GovXWrapper, a cross-chain wrapper contract that cooperates with OpenZeppelin's governance contracts to provide a safe and efficient governance process, strengthens the infrastructure of our platform. An unprecedented level of automation and computational intelligence is introduced with the advent of *Phala Network* and *Chainlink* Automation. The automation of vote and message claims on our platform, which ensures the precision and promptness of every governance action, depends on this interface. We guarantee that the governance process remains transparent and unchangeable by automating these essential processes.

### An Integrated Method for Decentralized Decision-Making

Beyond its technological capabilities, our platform excels thanks to a cutting-edge, user-friendly interface that puts the needs of its exceptional users first. We know that when decentralized governance is approachable and engaging, its full potential can be realized. As a result, our platform invites users to fully engage with the democratic process, serving as more than just a tool. Every decision is significant, every interaction is intuitive, and every member has a voice in this painstakingly created environment. Come along with us as we transform the DAO governance landscape by combining security, usability, and style to produce the best possible decentralized decision-making platform.

## Features

- **Cross-Chain Voting**: Aggregate voting power across Ethereum and zkEVM networks.
- **Seamless Integration**: Utilize the LXLY bridge to ensure fair representation of token balances between chains.
- **Automated Governance**: Employ Chainlink and Phala Network for automated vote and message claims.
- **User-Friendly Interface**: Engage users with an intuitive and interactive platform for decentralized decision-making.

## Technologies Used

- **Chainlink Automation**: Used Chainlink time-based trigger to execute the claim function every hour.
  - [UpKeep link]()
  - [Transactions]()

- **Phala Network**: To claim the message, we require specific Merkle proofs related to the source transaction for verification. These proofs are accessible through the [API](https://bridge-api.public.zkevm-test.net/bridges/). Our contract is linked to the Phat contract, which retrieves the necessary proofs from the API and transmits them to the contract to facilitate the message claiming process.
  - [Code]()
  - [Transaction]()

- **Polygon zkEVM**: VoteOnZkEVM contract was deployed on Polygon zkEVM Testnet.
  - [VoteOnZkEVM Contract]()

- **Goerli**: GovXWrapper contract was deployed on Goerli.
  - [GovXWrapper Contract]()
  - [Autoclaim Contract]()

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
- [Polygon](https://polygon.technology/)
- [OpenZeppelin](https://openzeppelin.com/)
- [Phala Network](https://phala.network/)

