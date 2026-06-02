# 02 — Network Selection: Choosing the Right EVM Chain

Deploying to the wrong network wastes gas and kills adoption.
Here is how to choose correctly.

---

## Supported Networks on Krionex

| Network | Type | Gas Cost | Best For |
|---------|------|----------|----------|
| Ethereum | L1 | High | Max credibility, DeFi, high-value tokens |
| Base | L2 | Very Low | Low cost, Coinbase ecosystem, growing fast |
| Polygon | L2 | Very Low | NFTs, gaming, high transaction volume |
| Arbitrum | L2 | Low | DeFi, speed, Ethereum security |
| BNB Chain | L1 | Low | Large user base, BSC ecosystem |
| Optimism | L2 | Low | OP Stack ecosystem, public goods |
| Avalanche | L1 | Low | Speed, enterprise, subnet use cases |

---

## How to Choose

### Choose Ethereum if:
- Your token needs maximum credibility
- You are integrating with major DeFi protocols
- Your users expect Ethereum mainnet
- Budget for higher gas is not a concern

### Choose Base if:
- You want very low gas costs
- Your users are Coinbase users
- You are building a consumer product
- You want fast growing ecosystem traction

### Choose Polygon if:
- You are launching NFTs or gaming assets
- You need very high transaction throughput
- Gas cost is a primary concern
- You need OpenSea visibility

### Choose Arbitrum if:
- You are building DeFi tooling
- You need Ethereum security with lower fees
- Your users are experienced DeFi users

### Choose BNB Chain if:
- Your target market is in Asia
- You need access to Binance user base
- Cost efficiency is critical

### Choose Optimism if:
- You are building on the OP Stack
- You want public goods funding eligibility
- You need Superchain compatibility

### Choose Avalanche if:
- You need high speed finality
- You are building enterprise use cases
- You want subnet architecture later

---

## Testnet First — Always

Before deploying to any mainnet, test on the testnet version:

| Mainnet | Testnet |
|---------|---------|
| Ethereum | Sepolia |
| Base | Base Sepolia |
| Polygon | Amoy |
| Arbitrum | Arbitrum Sepolia |
| BNB Chain | BSC Testnet |
| Optimism | OP Sepolia |
| Avalanche | Fuji |

Krionex supports both mainnet and testnet deployments.

---

## Deploy Across Multiple Networks

You can deploy the same contract to multiple networks 
from one Krionex configuration. No need to repeat setup.

→ [krionex.com](https://krionex.com)
