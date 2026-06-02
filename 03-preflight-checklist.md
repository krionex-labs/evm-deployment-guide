# 03 — Preflight Checklist: Before You Spend Gas

A failed deployment wastes real money.
Go through this checklist before every deployment.

---

## Contract Configuration Checklist

### ERC20
- [ ] Token name finalised (cannot change after deployment)
- [ ] Token symbol finalised (cannot change after deployment)
- [ ] Total supply decided
- [ ] Decimals set (18 is standard)
- [ ] Mintable or fixed supply decided
- [ ] Burnable needed?
- [ ] Pausable needed?
- [ ] Ownership model decided (single wallet or multisig)

### ERC721
- [ ] Collection name finalised
- [ ] Collection symbol finalised
- [ ] Metadata URI ready (Pinata or NFT.Storage)
- [ ] Max supply decided
- [ ] Mint price decided (free or paid)
- [ ] Royalty percentage set
- [ ] Reveal mechanic needed?

### ERC1155
- [ ] Token IDs planned
- [ ] Metadata URI format ready (must include {id})
- [ ] Supply per token ID decided
- [ ] Batch mint needed?

---

## Wallet Checklist

- [ ] Correct wallet connected
- [ ] Wallet has enough gas on target network
- [ ] You are on the correct network in your wallet
- [ ] Hardware wallet ready if using one

## Gas Estimates

| Network | Approx Deploy Cost |
|---------|-------------------|
| Ethereum | $20 — $80 |
| Base | $0.10 — $0.50 |
| Polygon | $0.01 — $0.10 |
| Arbitrum | $0.50 — $2.00 |
| BNB Chain | $0.50 — $2.00 |
| Optimism | $0.10 — $0.50 |
| Avalanche | $0.50 — $2.00 |

*Estimates vary with network congestion*

---

## Pre-Deployment Simulation

Krionex runs a preflight simulation before every deployment.
This catches configuration errors before you spend gas.

Common issues caught by simulation:
- Insufficient gas balance
- Invalid metadata URI format
- Contract configuration conflicts
- Network mismatch

---

## After Confirming — Do Not

- Do not close the browser tab
- Do not disconnect your wallet
- Do not switch networks mid-deployment
- Do not cancel the wallet transaction unless something looks wrong

→ [krionex.com](https://krionex.com)
