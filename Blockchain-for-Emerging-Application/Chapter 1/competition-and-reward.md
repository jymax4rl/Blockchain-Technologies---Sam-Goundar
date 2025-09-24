# Mining Competition and Block Reward

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
