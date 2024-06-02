# Smart Contracts Project

This repository contains smart contracts for implementing FT (Fungible Token) staking, an NFT (Non-Fungible Token) gate system, and FT token staking features. These contracts are designed to provide robust and secure functionalities for blockchain applications.

## Features

### 1. FT Token Staking
- **Stake FT Tokens**: Users can stake their FT tokens to earn rewards.
- **Unstake FT Tokens**: Users can withdraw their staked FT tokens along with the earned rewards.
- **View Staking Information**: Users can view their staking details including the amount staked, rewards earned, and staking duration.

### 2. NFT Token Gate System
- **Access Control**: Provides access control to certain features or content based on the ownership of specific NFTs.
- **Verify Ownership**: Users must prove ownership of required NFTs to access gated content or services.
- **Manage Gates**: Admins can create and manage gates, specifying which NFTs are required for access.

### 3. FT Token Staking
- **Stake FT Tokens for Additional Rewards**: Users can participate in a separate staking program to earn additional rewards.
- **Reward Calculation**: Rewards are calculated based on the staking duration and amount staked.
- **Unstake and Claim Rewards**: Users can unstake their tokens and claim their accumulated rewards.

## Getting Started

### Prerequisites
- Node.js
- NPM or Yarn
- Solidity Compiler

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/smart-contracts.git
    cd smart-contracts
    ```

2. Install dependencies:
    ```sh
    npm install
    ```
    or
    ```sh
    yarn install
    ```

### Deployment

1. Configure your environment variables. Create a `.env` file in the root directory and add the following:
    ```plaintext
    INFURA_PROJECT_ID=your_infura_project_id
    DEPLOYER_PRIVATE_KEY=your_private_key
    ```
2. Compile the smart contracts:
    ```sh
    npx hardhat compile
    ```
3. Deploy the smart contracts:
    ```sh
    npx hardhat run scripts/deploy.js --network your_network
    ```

### Usage

- **Staking FT Tokens**: Interact with the `FTStaking` contract to stake your tokens.
- **Using the NFT Gate System**: Verify NFT ownership and access gated content via the `NFTGate` contract.
- **Additional FT Token Staking**: Utilize the `AdditionalFTStaking` contract for enhanced rewards.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenZeppelin](https://openzeppelin.com/) for their secure smart contract library.
- [Infura](https://infura.io/) for their blockchain infrastructure.
- [Hardhat](https://hardhat.org/) for their excellent development environment.
