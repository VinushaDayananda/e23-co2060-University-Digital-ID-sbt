# Digital Student ID Using Soulbound Tokens

## Powered by Blockchain

## Introduction

This project presents a blockchain-based digital student identity system using Soulbound Tokens (SBTs) as a secure and non-transferable alternative to traditional physical student ID cards. The system is designed to address common issues associated with physical identification methods, such as loss, theft, duplication, and time-consuming manual verification processes.

The proposed solution utilizes blockchain technology to create decentralized digital identities for students. Each student is issued a unique Soulbound Token that is permanently linked to their blockchain wallet and cannot be transferred to another user. This ensures that the digital identity remains secure, tamper-resistant, and verifiable.

The system consists of three main layers: a blockchain layer that manages token ownership and revocation through smart contracts, a backend server that communicates with the blockchain and handles verification logic, and a web-based frontend that allows students and administrators to interact with the system. Students can connect their wallets, view their digital student IDs, and generate QR codes for identity verification, while administrators can issue and revoke tokens when necessary.

This project aims to demonstrate the feasibility of replacing traditional university ID cards with blockchain-based digital identities using Soulbound Tokens.

---

## Features

- Blockchain-based digital student identity
- Soulbound Token (non-transferable NFT) implementation
- Student wallet integration using MetaMask
- QR-based identity verification
- Token issuance and revocation system
- Web-based student and administrator interfaces
- Tamper-resistant identity verification

---

## System Architecture

The system consists of three main components:

### 1. Frontend Layer
- Student dashboard
- Administrator dashboard
- QR code generation and display
- Wallet connection using MetaMask

### 2. Backend Layer
- API services
- Blockchain communication
- Token verification logic
- Request handling

### 3. Blockchain Layer
- Smart contract deployment
- Token ownership management
- Non-transferable token enforcement
- Revocation mechanism

---

## Technologies Used

### Blockchain
- Ethereum / Polygon Test Network

### Smart Contract
- Solidity
- OpenZeppelin Contracts

### Backend
- Node.js
- Express.js
- Ethers.js

### Frontend
- HTML
- CSS
- JavaScript

### Wallet
- MetaMask

---

## Core Functionalities

- Connect student wallet
- Issue Soulbound Tokens
- Verify student identity
- Revoke tokens
- Generate QR codes
- Validate token ownership

---

## Project Structure

```plaintext
university-digital-id-sbt/
│
├── README.md
├── .gitignore
├── LICENSE
│
├── docs/
│   ├── architecture.md
│   ├── api_design.md
│   ├── smart_contract_design.md
│
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   ├── wallet.js
│   │   ├── student_dashboard.js
│   │   ├── admin_dashboard.js
│   │   ├── qr_generator.js
│   │   └── api.js
│   │
│   ├── pages/
│   │   ├── student_dashboard.html
│   │   ├── request_token.html
│   │   ├── verify_identity.html
│   │   ├── admin_dashboard.html
│   │   └── wallet_recovery.html
│
│   └── assets/
│       ├── images/
│       └── icons/
│
├── backend/
│   ├── app.py
│   ├── config.py
│   ├── requirements.txt
│   │
│   ├── database/
│   │   ├── db.py
│   │   └── schema.sql
│   │
│   ├── models/
│   │   ├── student_model.py
│   │   ├── token_model.py
│   │   ├── request_model.py
│   │   └── wallet_change_model.py
│   │
│   ├── routes/
│   │   ├── token_routes.py
│   │   ├── verification_routes.py
│   │   ├── admin_routes.py
│   │   └── student_routes.py
│   │
│   ├── services/
│   │   ├── blockchain_service.py
│   │   └── qr_service.py
│   │
│   └── utils/
│       ├── helpers.py
│       └── validators.py
│
├── blockchain/
│   ├── contracts/
│   │   └── StudentIdentitySBT.sol
│   │
│   ├── scripts/
│   │   ├── deploy.js
│   │   └── interact.js
│   │
│   ├── test/
│   │   └── contract_test.js
│   │
│   ├── hardhat.config.js
│   └── package.json
│
└── diagrams/
    ├── system_architecture.png
    ├── data_flow.png
    └── smart_contract_flow.png
