
# EVM Smart Contract Deployment Guide

A free, practical guide to deploying ERC20, ERC721, and ERC1155 
contracts across EVM networks — without the usual pain.

No fluff. No outdated tutorials. Just what actually matters.

---

## Who This Is For

- Founders launching a token or NFT collection
- Developers deploying contracts for clients
- Teams building on-chain products across multiple chains
- Anyone who has struggled with scattered deployment workflows

---

## Contents

| Guide | What It Covers |
|-------|---------------|
| [01 — Contract Types](./01-contract-types.md) | ERC20 vs ERC721 vs ERC1155 — which one you need |
| [02 — Network Selection](./02-network-selection.md) | Choosing the right EVM chain for your project |
| [03 — Preflight Checklist](./03-preflight-checklist.md) | What to verify before you spend gas |
| [04 — Verification](./04-verification.md) | How to get your contract verified on explorers |
| [05 — Post-Launch Operations](./05-post-launch-operations.md) | Mint, burn, pause — managing your contract after launch |

---

## Quick Reference — Supported EVM Networks

| Network | Best For | Avg Gas Cost |
|---------|----------|--------------|
| Ethereum | High-value tokens, max credibility | Higher |
| Base | Low cost, growing ecosystem | Very low |
| Polygon | NFTs, gaming, high throughput | Very low |
| Arbitrum | DeFi, L2 speed | Low |
| BNB Chain | Large user base, BSC ecosystem | Low |
| Optimism | OP Stack ecosystem | Low |
| Avalanche | Speed, enterprise use cases | Low |

---

## The Deployment Checklist

Before you deploy any contract, go through this:

- [ ] Contract type chosen (ERC20 / ERC721 / ERC1155)
- [ ] Token name and symbol finalized
- [ ] Total supply defined (ERC20)
- [ ] Metadata URI set (ERC721 / ERC1155)
- [ ] Target network selected
- [ ] Wallet funded with gas on target network
- [ ] Preflight simulation run
- [ ] Source verification planned

---

## Common Mistakes That Cost Money

**1. Deploying without a preflight simulation**
Gas wasted on failed transactions because configuration errors 
weren't caught beforehand.

**2. Forgetting to verify source code**
Unverified contracts look suspicious. Users and investors check.

**3. Deploying to mainnet before testing on testnet**
Always test on the testnet version of your target network first.

**4. No deployment records**
Six months later nobody knows which wallet deployed what, 
on which chain, with which tx hash.

**5. No post-launch operations plan**
Who can mint? Who can pause? Is there a multisig? 
Decide before launch, not after.

---

## Deploy Without Scripts

This guide covers the concepts. If you want a workspace that 
handles the full flow — configuration, simulation, deployment, 
verification, records, and operations — try Krionex free.

→ [krionex.com](https://krionex.com)
→ [Live mainnet examples](https://krionex.com/examples)

---

## Contributing

Found something outdated or wrong? Open a PR. 
This guide is maintained by the Krionex team and the community.

---

*Built by [Krionex](https://krionex.com) · 
[@krionexofficial](https://twitter.com/krionexofficial)*
