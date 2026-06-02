# 05 — Post-Launch Operations: Managing Your Contract After Launch

Deployment is not the finish line.
Here is everything you need to manage after your contract is live.

---

## Available Operations in Krionex

| Operation | What It Does | Who Needs It |
|-----------|-------------|--------------|
| Mint | Create new tokens | Projects with mintable supply |
| Burn | Permanently destroy tokens | Deflationary mechanics |
| Pause | Freeze all transfers | Emergency stop, security |
| Unpause | Resume transfers | After resolving an issue |

---

## Minting

Minting creates new tokens after the initial deployment.

**When to mint:**
- Staggered token release schedule
- Reward distributions
- NFT collection reveals
- Adding new token IDs (ERC1155)

**Important:** Only contracts deployed with the mintable 
feature enabled can mint after deployment. 
You cannot add minting to a non-mintable contract after launch.

---

## Burning

Burning permanently removes tokens from circulation.
The tokens are sent to the zero address and cannot be recovered.

**When to burn:**
- Deflationary tokenomics (reduce supply over time)
- Removing unsold tokens after a sale
- Token migration to a new contract
- Buyback and burn mechanics

---

## Pause and Unpause

Pausing freezes all token transfers across all wallets.
No one can send or receive while paused.

**When to pause:**
- Security incident detected
- Smart contract exploit discovered
- Emergency maintenance
- Regulatory compliance requirement

**Important:** Only contracts deployed with the pausable 
feature enabled can be paused. 
Plan this before deployment.

---

## Post-Launch Checklist

- [ ] Verify contract is showing correctly on explorer
- [ ] Test a small transfer to confirm it works
- [ ] Add token to CoinGecko or CoinMarketCap if applicable
- [ ] Import token contract into your workspace for operations
- [ ] Set up monitoring for unusual activity
- [ ] Document your contract address and tx hash securely
- [ ] Add token to MetaMask and test wallets

---

## Importing an Existing Contract

If you deployed a contract outside Krionex you can still 
import it into your workspace for operations.

Go to your Krionex workspace → Import Contract → 
Paste contract address → Select network → Connect

→ [krionex.com](https://krionex.com)
