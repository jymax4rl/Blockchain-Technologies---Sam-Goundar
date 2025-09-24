# 3.2 Integrity and Transparency

> *"Blockchain technology replaces traditional data storage technology as it is publicly verifiable, aided by transparency and integrity. A user present in a blockchain network can trust that the information they are accessing through a blockchain is tamper-proof and uncorrupted from the instant it was logged and recorded. Every user can authenticate the information added over the blockchain. Blockchain does not leave behind past records, and as the data is added to the blockchain, it appends and grows while also providing current information (Zheng et al., 2018). Merkle trees ensure the integrity of the data by hashing the transactions to a single root."*  
— Zheng et al., 2018

## My Understanding

### Integrity
- Once recorded, blockchain data is **tamper-proof** and **uncorrupted**.  
- Users can independently **verify authenticity** without trusting a central authority.  

### Transparency
- Data on a public blockchain is **openly verifiable** by all participants.  
- Everyone can check the history of transactions, ensuring **trust and accountability**.  

### Append-Only Growth
- Blockchain **never deletes old records**.  
- New data is always **appended**, so the ledger keeps growing while also providing the most current state.  

### Merkle Trees
- A **Merkle tree** is used to hash all transactions into a single **Merkle root**.  
- The Merkle root is stored in the block header.  
- If even one transaction changes, the root changes, making tampering obvious.  
- Benefits:
  - ✅ Ensures integrity of all transactions in a block.  
  - ✅ Allows efficient verification without needing the full dataset.  

## Key Takeaway
Blockchain ensures **trust, transparency, and immutability**.  
Merkle trees make it possible to quickly and securely detect any attempt to alter past data.
