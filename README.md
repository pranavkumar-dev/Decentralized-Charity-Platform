# Decentralized Charity Platform

A blockchain-based platform that enables transparent and trustless charitable donations using Ethereum smart contracts. This platform allows charities to register fundraising campaigns and donors to contribute directly to causes they care about, with all transactions recorded on the blockchain for complete transparency.

## 🌟 Features

- **Charity Registration**: Charities can register campaigns with names, descriptions, and funding goals
- **Transparent Donations**: All donations are recorded on the Ethereum blockchain
- **Automatic Fund Release**: Funds are automatically released to charities when goals are met
- **Web3 Integration**: Seamless wallet connection using MetaMask
- **Real-time Updates**: Live status updates for all transactions
- **Smart Contract Security**: Built with Solidity best practices and security measures

## 🏗️ Architecture

The platform consists of three main components:

1. **Smart Contract** (`CharityPlatform.sol`): Ethereum smart contract handling all business logic
2. **Frontend Interface** (`index.html`, `styles.css`): User-friendly web interface
3. **Web3 Integration** (`script.js`): JavaScript code for blockchain interaction

## 🚀 Getting Started

### Prerequisites

- [MetaMask](https://metamask.io/) browser extension installed
- Ethereum wallet with some test ETH (for testing on testnets)
- Basic understanding of Web3 and blockchain concepts

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Decentralized-Charity-Platform
```

2. Deploy the smart contract:
   - Use [Remix IDE](https://remix.ethereum.org/) or your preferred Solidity development environment
   - Compile and deploy `CharityPlatform.sol` to your desired Ethereum network
   - Update the `contractAddress` in `script.js` with your deployed contract address

3. Open `index.html` in a web browser

### Usage

#### For Charities

1. **Connect Wallet**: Click "Connect Wallet" and approve the MetaMask connection
2. **Register Campaign**: Fill in the charity name, description, and goal amount
3. **Submit Registration**: Click "Register Charity" to create your campaign
4. **Monitor Progress**: Track donations and campaign status

#### For Donors

1. **Connect Wallet**: Connect your MetaMask wallet to the platform
2. **Browse Campaigns**: View registered charities and their details
3. **Make Donation**: Enter the charity ID and donation amount
4. **Confirm Transaction**: Approve the transaction in MetaMask

## 📋 Smart Contract Functions

### Core Functions

- `registerCharity(string name, string description, uint256 goalAmount)`: Register a new charity campaign
- `donate(uint256 charityId)`: Donate ETH to a specific charity
- `getCharityDetails(uint256 charityId)`: Retrieve charity information
- `releaseFunds(uint256 charityId)`: Automatically release funds when goal is met

### Events

- `CharityRegistered`: Emitted when a new charity is registered
- `DonationReceived`: Emitted when a donation is made
- `FundsReleased`: Emitted when funds are released to a charity

## 🔧 Technical Details

### Smart Contract

- **Language**: Solidity ^0.8.0
- **License**: MIT
- **Network**: Compatible with any EVM-compatible blockchain
- **Security**: Includes input validation and access controls

### Frontend

- **Framework**: Vanilla JavaScript with HTML/CSS
- **Web3 Library**: Ethers.js v5.0
- **Wallet Integration**: MetaMask
- **Responsive Design**: Mobile-friendly interface



---

**Built with ❤️ for the Ethereum community** 
