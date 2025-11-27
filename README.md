# Catalyst HOTEL-NFT AI Engine & AikenSmartContract

This repository contains the prototype implementation of **HOTEL-NFT**, a next-generation hotel booking system that integrates **AI-driven recommendations**, **CIP-68 dynamic NFTs**, and **Aiken SmartContract**.  
The system automates hotel booking, escrow payments, user identity verification, and reputation updates directly on-chain.

---

## 📚 Repository Structure
```
/contracts
    BookingEscrow.hs      -- Main booking escrow logic
    CIP68Minting.hs       -- NFT minting + reference scripts
    NFTRedeemer.hs        -- Updating NFT metadata

/ai-engine
    profile_generator.py  -- AI Workflow: inputs → JSON profile
    metadata_builder.py   -- Converts AI profile → CIP-68 Metadata

/frontend
    booking-ui/           -- Booking + AI assistant interface
    nft-viewer/           -- View NFT metadata + history

/scripts
    mint_nft.sh           -- Local test minting
    update_nft.sh         -- Metadata update test
    deploy_testnet.sh     -- End-to-end deployment script
```

---

## 🧠 AI Engine Features
- Customer need analysis  
- Preference scoring  
- Matching engine (room → traveler profile)  
- DID verification scoring  
- Reputation estimation (CVC Score)  
- Outputs standardized **Booking Profile JSON**

### Example output:
```json
{
  "location": "Vung Tau",
  "budget": 120,
  "people": 2,
  "style": "Chill",
  "preferences": ["sea_view", "breakfast"],
  "did_hash": "abc123...",
  "cvc_score": 82
}
```

---

## 💎 Smart Contract Highlights
- AI-generated booking profile → On-chain NFT minting
- CIP-68 Dynamic NFT for booking updates
- Escrow Contract for ADA payments
- DID Integration
- Reputation Engine
- On-chain traceability

---

## 🛠 Development Tools
- [Haskell](https://github.com/input-output-hk/haskell.nix)
- [Aiken](https://github.com/aiken-lang)
- [Lucid](https://github.com/spacebudz/lucid)
- [Cardano CLI](https://docs.cardano.org/)
- [Postman / Python](https://www.python.org/downloads/)
- [Figma](https://www.figma.com/)
- [Next.js](https://nextjs.org/docs)

---

## 📦 Clone Repository
```bash
git clone https://github.com/DUALCORE-VuNam/HOTEL-NFT-AI-BLOCKCHAIN-CARDANO.git
cd HOTEL-NFT-AI-BLOCKCHAIN-CARDANO
```
