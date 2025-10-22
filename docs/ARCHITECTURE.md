# 🧱 Technical Architecture Overview

## 1️⃣ Smart Contracts
Built on **Solana** using the **Anchor framework**.
Modules include:
- Margin & Leverage Manager
- Funding Rate Oracle
- Liquidation Engine
- DAO Governance Contract
- Treasury Controller

## 2️⃣ Oracle Integration
Price feeds from:
- **Pyth Network** (real-time Solana price data)
- **Switchboard** (customized feeds for meme tokens)

## 3️⃣ API Layer
The **MemePerps API** provides:
- Trade indexing
- Burn events
- Listing status
- Historical market data

## 4️⃣ Frontend Stack
- React + Vite  
- TailwindCSS + Framer Motion  
- Solana Wallet Adapter  
- GraphQL for data fetching

## 5️⃣ DAO & Treasury
- Treasury addresses managed by smart contracts  
- Voting and execution powered by $MPERP staking  
- Burn execution events visible on-chain
