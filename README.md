# Pi Network Subscription Smart Contract - Implementation Proof

This repository showcases the first successful implementation of a recurring payment system on the **Pi Network Testnet** using **Soroban Smart Contracts**. Based on the **PiRC2** request for comments, this project demonstrates a non-custodial subscription model.

## 🚀 Achievement
Successfully deployed and executed a "Merchant-Subscriber" lifecycle where:
1. **Merchant** registers a service with a fixed price and billing period.
2. **Subscriber** opts-in via a smart contract call.
3. **Automated Transfer** of 1 Pi occurs instantly upon subscription.
4. **Token Allowance** is set for future recurring billing cycles.

## 🛠 Technical Stack
- **Contract Language:** Rust (Soroban SDK)
- **Network:** Pi Testnet
- **Backend:** Deno Edge Functions
- **Database:** Supabase (for transaction indexing)

## 📊 Proof of Execution
- **Contract ID:** `CAG3UWYIL2FAOTAI4TP7YZGGIMWAMTAABRCVJERHCDWP4JDYKUAS65SB`
- **Verified Transaction:** `99db18b46b787528701a2956812e4196e52412107f3dbbc9be3d81c4434fdfe4`
