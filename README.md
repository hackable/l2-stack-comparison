# L2 Stacks Comparison Table


| Feature / Criteria                   | zkSync                              | Optimism                            |
|--------------------------------------|-------------------------------------|-------------------------------------|
| **Type of Solution**                 | zk-Rollup                           | Optimistic Rollup                   |
| **Security Mechanisms**              | Zero-knowledge proofs               | Fraud proofs                        |
| **Security Assumptions**             | Assumes cryptographic security of zk-SNARKs | Assumes honesty in the majority of network validators |
| **Throughput (TPS)**                 | High                           | Medium |
| **Latency**                          | Lower than Ethereum                 | Lower than Ethereum but higher than zkSync |
| **Consensus Mechanism**              | Inherits Ethereum's security        | Inherits Ethereum's security        |
| **Data Availability**                | On-chain data storage               | On-chain data storage               |
| **Smart Contract Compatibility**     | Full EVM compatibility planned      | Full EVM compatibility              |
| **Interoperability**                 | Ethereum mainnet                    | Ethereum mainnet                    |
| **Cost Efficiency**                  | Lower transaction costs due to zk-Rollup efficiency | Lower transaction costs than Ethereum but generally higher than zkSync |
| **Developer Support**                | Growing community and tooling       | Extensive community and tooling     |
| **Tokenomics**                       | zkSync native token for protocol governance and fee discounts | Optimism uses a native token for governance and transaction fees |
| **Scalability Features**             | Scalability through batched proof submissions | Scalability through sequential transaction processing with delayed finality |
| **User Experience**                  | Near-instant transaction finality   | Delayed transaction finality (one week for disputes) |
| **Compliance & Regulation**          | Similar compliance challenges as other L2 solutions | Similar compliance challenges as other L2 solutions |
| **Integration Complexity**           | Moderate, with full EVM support in future versions | Moderate, already supports full EVM |
| **Upgradeability and Maintenance**   | Regular updates and protocol improvements | Regular updates and community-driven protocol improvements |
| **Specific Use-cases Supported**     | Suitable for applications requiring high transaction throughput and security | Suitable for general DApps, particularly those transferring from Ethereum without major changes |
| **Transaction Finality**             | Faster due to zk proofs            | Slower due to the challenge period required for fraud proofs |
| **Privacy Features**                 | Potential for higher privacy with zk technology | Standard privacy similar to Ethereum |
| **Decentralization Level**           | High, with a focus on maintaining Ethereum's decentralization ethos | High, also maintains Ethereum's decentralization ethos |
| **L3 Support**                       | Emerging support for L3 applications | Plans for L3 scaling solutions and increased abstraction |
| **Cross-Chain Messaging**            | Limited current capabilities but plans for expansion | Supports cross-chain messaging through protocols like Nomad and Connext |
| **Cost for Settlement Layer in ETH** | Lower due to efficient proof aggregation and fewer on-chain transactions | Typically higher due to individual transaction proofs requiring more frequent on-chain data posting |

- **zkSync**: The use of zk-Rollups allows for efficient compression of transaction data and batch verification, significantly reducing the amount of data that must be processed and stored on the Ethereum mainnet. This leads to lower costs for settling transactions back on Ethereum.
- **Optimism**: Since Optimistic Rollups require each transaction to be posted individually and involve a challenge period for dispute resolution, they generally incur higher costs for data posting and final settlement on Ethereum compared to zk-Rollups.
