# Pi Network Subscription Smart Contract - Implementation Proof

This repository showcases the first successful implementation of a recurring payment system on the **Pi Network Testnet** using **Soroban Smart Contracts**. Based on the **PiRC2** standard, this project demonstrates a non-custodial subscription model for the Pi ecosystem.

## 🚀 Achievement
Successfully deployed and executed a "Merchant-Subscriber" lifecycle where:
1. **Merchant** registers a service with a fixed price and billing period.
2. **Subscriber** opts-in via a smart contract call.
3. **Automated Transfer** of 1 Pi occurs instantly upon subscription.
4. **Token Allowance** is set for future recurring billing cycles.

## 🔗 Live Demo (Access via Pi Browser Only)
You can experience the implementation live through the following links:

* **Mainnet Version:** [https://sallanet.pi](https://sallanet.pi)
* **Testnet Version:** [https://sallashop.vercel.app](https://sallashop.vercel.app)

> **Note:** These links must be opened inside the **Pi Browser** to interact with the Pi Wallet and Blockchain.

## 🛠 Technical Stack
- **Contract Language:** Rust (Soroban SDK)
- **Network:** Pi Testnet / Mainnet
- **Backend:** Deno Edge Functions
- **Database:** Supabase (Indexing & Logs)

## 📊 Proof of Execution (Testnet)
- **Contract ID:** `CAG3UWYIL2FAOTAI4TP7YZGGIMWAMTAABRCVJERHCDWP4JDYKUAS65SB`
- **Verified Tx:** `99db18b46b787528701a2956812e4196e52412107f3dbbc9be3d81c4434fdfe4`
