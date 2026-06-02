# 04 — Verification: Getting Your Contract Verified on Explorers

An unverified contract looks suspicious.
Verification is not optional if you want users to trust your token.

---

## What Verification Means

Verification publishes your Solidity source code on the block explorer
so anyone can read exactly what your contract does.

**Unverified contract:**
Users see raw bytecode. Cannot read the logic. Looks shady.

**Verified contract:**
Users see clean readable Solidity code. Trust established.

---

## Where Contracts Get Verified

| Network | Explorer | Verification Site |
|---------|----------|------------------|
| Ethereum | Etherscan | etherscan.io |
| Base | Basescan | basescan.org |
| Polygon | Polygonscan | polygonscan.com |
| Arbitrum | Arbiscan | arbiscan.io |
| BNB Chain | BscScan | bscscan.com |
| Optimism | Optimistic Etherscan | optimistic.etherscan.io |
| Avalanche | Snowtrace | snowtrace.io |

---

## How Krionex Handles Verification

Krionex triggers automatic verification after every deployment.
You do not need to manually submit source code to the explorer.

After deployment you will see:
- Verification status in your workspace
- Direct explorer link to the verified contract
- Green checkmark on the explorer contract page

---

## If Verification Fails

Occasionally verification can fail due to network delays.
If this happens:

1. Go to your deployment record in Krionex
2. Copy your contract address
3. Go to the relevant explorer
4. Click Verify and Publish
5. Select Solidity Single File
6. Match the compiler version exactly
7. Paste the source code
8. Submit

---

## What a Verified Contract Looks Like

On Etherscan a verified contract shows:
- Green checkmark next to the contract address
- Full source code under the Contract tab
- Read Contract and Write Contract functions visible
- ABI available for download

This is what builds trust with your users, investors, and the community.

→ [krionex.com](https://krionex.com)
