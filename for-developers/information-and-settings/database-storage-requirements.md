# Database Storage Requirements

The configuration variable `db_storage` can be used to define the amount of storage allocated to your RDS instance. The chart below shows an estimated amount of storage that is required to index individual chains. The `db_storage` can only be adjusted 1 time in a 24 hour period on AWS.

| Chain            | Storage (GiB) |
| ---------------- | ------------- |
| POA Core         | 80            |
| POA Sokol        | 60            |
| Ethereum Classic | 250           |
| Ethereum Mainnet | 3800          |
| Kovan Testnet    | 250           |
| Ropsten Testnet  | 5700          |
| xDai             | 40            |

