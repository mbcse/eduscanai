# EduScanAI Explorer - AI-Powered Blockchain Explorer for EduChain

## Overview
EduScanAI Explorer is an advanced AI-powered blockchain transaction analyzer designed specifically for EduChain. It provides deep insights into blockchain transactions, addresses, tokens, and NFTs by leveraging AI to interpret transaction data meaningfully. EduScanAI enables users to understand what happens in a transaction beyond just technical details, providing an intuitive and human-like explanation.

## Key Features
- **AI-Powered Transaction Analysis**: Generates detailed and intuitive explanations for transaction activity.
- **Comprehensive Transaction Breakdown**: Provides insights into transfers, swaps, contract interactions, and costs.
- **Security Risk Assessment**: Analyzes contract verifications and potential security risks.
- **Address & Token Analysis**: Supports wallet address analytics and token metadata retrieval.
- **Efficient Gas Cost Analysis**: Evaluates gas efficiency and transaction costs.

## System Architecture
### Technical Flow Diagram
Below is the architecture diagram illustrating how EduScanAI processes transaction analysis:

![EduScanAI Architecture](./eduscanai.png)

### Components Breakdown
1. **Client**: Sends transaction hash or address details for analysis.
2. **Agent**: Central AI entity handling requests, interfacing with LLM, and returning structured responses.
3. **LLM (Large Language Model)**: Enhances analysis by interpreting blockchain data into a human-readable format.
4. **Data Fetcher & Processor**: Fetches and processes transaction data from EduChain.
5. **Chain Manager**: Handles interactions within the EduChain blockchain.
6. **Event Processor**: Deciphers contract calls, token movements, and smart contract interactions.
7. **Token Metadata Manager**: Retrieves metadata for tokens and NFTs to enhance understanding.
8. **Tool Calls**: Additional utilities for improving data interpretation.

## Installation and Setup
### Prerequisites
- Node.js (v16+ recommended)
- Yarn (Package Manager)
- Docker (Optional, for running services locally)

### Installation
```sh
git clone https://github.com/yourrepo/eduscanai.git
cd eduscanai
yarn install
