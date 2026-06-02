# 01 — Contract Types: ERC20 vs ERC721 vs ERC1155

Choosing the wrong contract type is the most common mistake 
before deployment. Here is exactly which one you need.

---

## ERC20 — Fungible Token

Every token is identical and interchangeable.
1 token = 1 token. Like currency.

**Use ERC20 when you are building:**
- A cryptocurrency or utility token
- A governance token for a DAO
- A reward or points system
- A stablecoin or wrapped asset

**Key properties:**
| Property | Value |
|----------|-------|
| Tokens identical | Yes |
| Divisible | Yes (up to 18 decimals) |
| Transferable | Yes |
| Supply | Fixed or mintable |

**Examples:** USDC, UNI, LINK, SHIB

---

## ERC721 — Non-Fungible Token (NFT)

Every token is unique. Token #1 is different from Token #2.

**Use ERC721 when you are building:**
- An NFT art collection
- Membership or access passes
- In-game items where each item is unique
- Digital certificates or credentials
- Domain names or identity assets

**Key properties:**
| Property | Value |
|----------|-------|
| Tokens identical | No — each is unique |
| Divisible | No |
| Metadata | Required (URI per token) |
| Supply | Usually limited collection |

**Examples:** CryptoPunks, BAYC, ENS domains

---

## ERC1155 — Multi-Token Standard

One contract can hold both fungible and non-fungible tokens.
Most flexible option.

**Use ERC1155 when you are building:**
- A game with multiple item types (swords, potions, characters)
- A platform with both fungible and non-fungible assets
- NFT editions where multiple copies of the same item exist
- Any project needing gas-efficient batch transfers

**Key properties:**
| Property | Value |
|----------|-------|
| Multiple token types | Yes |
| Fungible + NFT in one | Yes |
| Batch transfers | Yes — gas efficient |
| Metadata | Required (URI with {id}) |

**Examples:** OpenSea shared storefront, most Web3 games

---

## Quick Decision Guide
Do you need unique one-of-one tokens?
YES → ERC721
Do you need multiple copies of items OR a mix of fungible and non-fungible?
YES → ERC1155
Do you need a simple transferable token with supply?
YES → ERC20

---

## Deploy Your Contract
→ [krionex.com](https://krionex.com)
