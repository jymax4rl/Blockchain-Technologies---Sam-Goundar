# 🧾 Ethereum Accounts

## Overview
- Accounts are the **main building blocks** of the Ethereum ecosystem.  
- All **interactions** in Ethereum happen between accounts, stored as **transactions** in the ledger.  
- Every account has a **balance** (amount of Ether it holds).  

---

## Types of Accounts
Ethereum has **two types of accounts**:

### 1. Externally Owned Accounts (EOAs)
- Controlled by **people** (via private keys).  
- **Private key**: kept secret by the owner.  
- **Public address**: identity of the account (first 160 bits of the public key).  
- Can:
  - Hold Ether.  
  - Send transactions to other EOAs.  
  - Interact with contract accounts.  
- ⚡ Key point: EOAs **do not contain code**.

---

### 2. Contract Accounts
- Represent **smart contracts**.  
- Identified by a **public address**.  
- Do **not** have private keys.  
- Can:
  - Hold Ether.  
  - Contain code (functions + state variables).  
  - Be triggered by transactions from EOAs or other contracts.  

---

## 🔑 Essential Difference
- **EOA** → Owned by a person, requires a private key, no code.  
- **Contract Account** → Owned by code, no private key, executes smart contracts.  

---

## Analogy
- **Externally Owned Account (EOA)** = Your **personal bank account**. You control it with your signature (private key).  
- **Contract Account** = A **vending machine**. It holds money, runs code (dispenses items), and acts automatically when triggered.
