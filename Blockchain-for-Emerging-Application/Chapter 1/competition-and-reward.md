# Mining Competition and Block Reward

## Question
Isn’t one block too much for a single miner? What if one miner becomes too powerful?

## Explanation
- Only **one miner (or pool)** can win each block, otherwise the chain would fork uncontrollably.  
- Bitcoin adjusts **difficulty** so that a block is mined roughly every 10 minutes.  
- If one miner controls >50% of hashrate, they could attempt a **51% attack**, but incentives make this self-defeating.

## ASCII Diagram

             ┌─────────────┐      ┌─────────────┐      ┌─────────────┐
             │ Miner A     │      │ Miner B     │      │ Miner C     │
             │ (hashes...) │      │ (hashes...) │      │ (hashes...) │
             └──────┬──────┘      └──────┬──────┘      └──────┬──────┘
                    │                    │                    │
                    │   Compete to find the next valid block  │
                    └────────────────────┬────────────────────┘
                                         │
                                         ▼
                                ┌─────────────────┐
                                │   New Block!    │
                                │ (10 min avg.)   │
                                └───────┬─────────┘
                                        │
                                        ▼
                             ┌─────────────────────┐
                             │ Winner: Miner B     │
                             │ Reward: 12.5 BTC    │
                             │ + transaction fees  │
                             └─────────────────────┘

## Takeaway
- The reward is “big” because mining is costly and competitive.  
- Monopoly is discouraged by difficulty adjustment + economic incentives.
