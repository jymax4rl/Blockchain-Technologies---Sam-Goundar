# Block Rewards and Consensus

> *"The miner receives a reward for running the consensus algorithms; the current reward is 12.5 BTC in the Bitcoin blockchain and 2 ETH in the Ethereum blockchain."*  
> — Xu et al., 2019

### My Understanding
- The **12.5 BTC reward** refers to the *block reward*, which is given to miners **each time a block is successfully mined and added to the blockchain**.  
- In addition to this fixed reward, miners also collect **transaction fees** from the block.  
- The block reward is **not constant** — it undergoes a “halving” roughly every 4 years in Bitcoin.  
  - 2009 → 50 BTC  
  - 2012 → 25 BTC  
  - 2016 → 12.5 BTC  
  - 2020 → 6.25 BTC  
  - 2024 → 3.125 BTC (current)  

### Ethereum Context
- Ethereum formerly rewarded **2 ETH per block** under Proof of Work.  
- Since **The Merge (Sept 2022)**, Ethereum uses **Proof of Stake** — validators earn rewards for securing the chain instead of miners.  

### Key Takeaway
The block reward incentivizes participation in consensus. It ensures that miners (or validators, in Ethereum’s case) are compensated for the energy and resources they spend to secure the blockchain.




# Do Miners Earn a Block Reward for Every Transaction?

> *"The miner receives a reward for running the consensus algorithms; the current reward is 12.5 BTC in the Bitcoin blockchain..."*  
> — Xu et al., 2019

### Question
If I send 0.00022 BTC, does the miner really get 12.5 BTC just for validating my tiny transaction?

### Explanation
- A **block is not created per transaction**.  
- Instead, Bitcoin groups many pending transactions into one **block** (about every 10 minutes).  
- When a miner successfully mines that block:  
  - They earn the **block reward** (e.g., 12.5 BTC in 2019, 3.125 BTC in 2024).  
  - Plus all the **transaction fees** from the transactions inside the block.  

### Key Insight
- Your 0.00022 BTC transaction is just *one entry* in a block.  
- The miner does **not** earn 12.5 BTC because of *your* transaction.  
- The block reward exists to keep miners incentivized to secure the chain, regardless of transaction sizes.  

### Analogy
Think of a block like a **shipping container**:  
- Your transaction is one **package** inside it.  
- The miner gets paid for shipping the **entire container**, not for each individual package.  
- You only contribute your small **shipping fee** (transaction fee).






# Do Multiple Miners Share the Block Reward?

### Question
If many miners validate the same block, do they split the 12.5 BTC reward?

### Explanation
- In Bitcoin, **only one miner (or pool)** actually wins the right to add the block.  
- That miner receives the **entire block reward** (12.5 BTC in 2019, 3.125 BTC today) **plus all transaction fees** in that block.  
- The other miners don’t earn from that block; they just continue competing for the next one.  

### Mining Pools
- Most miners don’t mine alone; they join **pools** to reduce risk.  
- If the pool mines a block, the reward goes to the **pool operator**, who then distributes it among participants.  
- Distribution is based on each miner’s contributed computing power (hashrate).  

### Key Insight
- Rewards are not shared among all miners in the world.  
- They are only shared **inside a mining pool** if the pool wins a block.  



