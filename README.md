---
## ✅ Repository Name: `HOTEL-NFT-AI-BLOCKCHAIN-CARDANO`
## ✅ Link Info Proposal: `https://dualcore.gitbook.io/hotel-nft-dualcore-team`
## ✅ Introduction Video: `https://www.youtube.com/watch?v=YLXq5LgvfTc`
## ✅ Whitepaper HOTEL-NFT 1.0: `https://dualcore.gitbook.io/hotel-nft-dualcore-team/summary/hotel-nft-whitepaper-1.0`
# `README.md` Content:
```markdown
# Catalyst HOTEL-NFT AI & Smart Contracts

This repository contains the prototype implementation of **HOTEL-NFT**, a next-generation hotel booking system that integrates **AI-driven recommendations**, **CIP-68 dynamic NFTs**, and **Aiken SmartContract**.  
The system automates hotel booking, escrow payments, user identity verification, and reputation updates directly on-chain.

## 📚 Repository Structure
/contracts
BookingEscrow.hs -- Main booking escrow logic
CIP68Minting.hs -- NFT minting + reference scripts
NFTRedeemer.hs -- Updating NFT metadata

/ai-engine
profile_generator.py -- AI Workflow: inputs → JSON profile
metadata_builder.py -- Converts AI profile → CIP-68 Metadata

/frontend
booking-ui/ -- Booking + AI assistant interface
nft-viewer/ -- View NFT metadata + history

/scripts
mint_nft.sh -- Local test minting
update_nft.sh -- Metadata update test
deploy_testnet.sh -- End-to-end deployment script

## 🧠 AI Engine Features
- Customer need analysis  
- Preference scoring  
- Matching engine (room → traveler profile)  
- DID verification scoring  
- Reputation estimation (CVC Score)  
- Outputs standardized **Booking Profile JSON**

Example output:
```json
{
  "location": "Da Nang",
  "budget": 120,
  "people": 2,
  "style": "Chill",
  "preferences": ["sea_view", "breakfast"],
  "did_hash": "abc123...",
  "cvc_score": 82
}

## 💎 Smart Contract Highlights
- AI-generated booking profile → On-chain NFT minting
- CIP-68 Dynamic NFT for booking updates (check-in, completion, reputation)
- Escrow Contract for ADA payment & booking guarantee
- DID Integration (Atala PRISM / 3rd-party DID provider)
- Reputation Engine (CVC Score) updated by smart contract
- End-to-end on-chain traceability

🛠️ Development Tools
-[Haskell] / Plutus Tx — Core smart contracts (https://github.com/input-output-hk/haskell.nix)
-[Aiken] (optional for modular contract logic)(https://github.com/aiken-lang)
-[Lucid] — Frontend integration & manual testing(https://github.com/spacebudz/lucid) for manual testing
-[Cardano CLI] — On-chain testing & deployment(https://docs.cardano.org/) 
-[Postman / Python] — AI workflow debugging(https://www.python.org/downloads/)
-[Figma] — UI flow & prototype(https://www.figma.com/)
-[Next.js] — Booking frontend demo(https://nextjs.org/docs)


```bash
git clone https://github.com/DUALCORE-VuNam/HOTEL-NFT-AI-BLOCKCHAIN-CARDANO.git
cd HOTEL-NFT-AI-BLOCKCHAIN-CARDANO

  






