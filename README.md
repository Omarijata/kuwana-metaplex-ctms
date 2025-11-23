# kuwana-metaplex-ctms
Open-source Metaplex standard for RWA commodity tokenization and automated farmer royalty payouts.

## 🎯 Project Overview

Kuwana Protocol is building the necessary infrastructure for Real-World Asset (RWA) tokenization on Solana. We enable fractional ownership of productive assets through Metaplex NFTs with automated revenue distribution.

### Key Features
- **Metaplex CORE RWA-NFTs** for franchise ownership
- [cite_start]**New DeFi Primitive:** Immutably automated 50/40/10 revenue distribution to NFT holders and the DAO Treasury [cite: 585-587].
- **Open-source smart contract templates** for any business to tokenize
- **Unrivaled Access:** Strategic alignment with COCOBOD-authorized processors to tokenize the revenue streams of the region that produces over 60% of the world's cocoa output.

## 🏗️ Architecture & Scope

### Phase 1: Technical Infrastructure (Grant-Funded MVP)
This phase is funded by the Metaplex DAO Grant.

| Deliverable | Description |
| :--- | :--- |
| **Metaplex CORE CTMS Contracts** | **Open-Source** smart contract suite including the Commodity Token Metadata Standard (CTMS) and the 50/40/10 logic. |
| **Revenue Distribution Plugin** | Logic for integrating off-chain sales data and triggering the on-chain payout split. |
| **Investor Dashboard** | Frontend (React/Next.js) for the Investor Dashboard and functional **Simulated Revenue Demo** environment. |
| **Documentation** | Full technical documentation and public tutorials for Metaplex developers. |

### Phase 2: Physical Deployment (Equity Funded)
- Jollof Spot franchise units (3-5 locations)
- Real revenue integration from operational units.
- Full deployment of the GovTech Commodities Pilot.

## 🛠️ Tech Stack

- **Blockchain:** Solana
- **NFT Standard:** Metaplex CORE + CTMS extension
- **Smart Contracts:** Anchor Framework
- **Frontend:** React + Next.js + Solana web3.js
- **Wallet Integration:** Phantom, Solflare
- **Oracles:** Chainlink (price feeds) + custom revenue oracle
- **Payments:** Solana Pay (cross-border transfers)

## 📂 Repository Structure

kuwana-metaplex-ctms/ ├── contracts/ # Metaplex CORE CTMS smart contracts (coming soon) │ ├── franchise_nft.rs # Franchise tokenization │ ├── commodity_nft.rs # Commodity tokenization │ ├── revenue_dist.rs # 50/40/10 distribution logic │ └── ctms_standard.rs # CTMS metadata standard ├── app/ # Frontend application (coming soon) │ ├── dashboard/ # Investor dashboard │ ├── marketplace/ # NFT trading │ └── mint/ # NFT minting interface └── docs/ # Documentation & tutorials (coming soon) ├── CTMS_SPEC.md # CTMS metadata specification ├── ARCHITECTURE.md # System architecture └── TUTORIALS.md # Developer guides

## 🚧 Development Status

**Last Updated:** November 23, 2025
**Current Phase:** Grant application & prototype development

### Timeline:

| Phase | Duration | Status |
| :--- | :--- | :--- |
| **Grant Submission** | November 2025 | ✅ Submitted (MetaplexDAO, Solana Finternet) |
| **Phase 1 Build (MVP)** | Dec 2025 - Jan 2026 | 🔜 Smart contract development begins (upon funding) |
| **MVP Launch** | Feb 2026 | 🔜 MVP launch on Solana devnet & CTMS specification published |
| **Physical Deployment** | Q2 2026 | 🔜 Jollof Spot pilot (3 units in Pretoria) |
| **Scaling** | Q3 2026 | 🔜 Launch commodity tokenization (cocoa) |

## 🤝 Contributing

This project is open-source (MIT License). Contributions are welcome once development begins.

### Areas We Need Help:
- Solana/Anchor smart contract development
- Metaplex CORE plugin architecture
- Oracle integration (Chainlink + custom)
- Documentation & tutorials
- Security auditing

## 📧 Contact

**Daniel Tettey Addy**
Founder & CEO, Kuwana Protocol
**Email:** tettey@kuwanaprotocol.com
**Phone:** +27 72 265-3294 (South Africa)
**Location:** Innovation Hub, Pretoria, South Africa
**LinkedIn:** [https://www.linkedin.com/in/marijata/]
**Twitter:** [@KuwanaProtocol] (coming soon)

## 📄 License

MIT License - See **LICENSE** file for details

---
### 🔗 Links & Resources

**Investor Website:** [kuwanaprotocol.com]
**GitHub Repository:** https://github.com/Omarijata/kuwana-metaplex-ctms
**MetaplexDAO Grant Application:** [Pending]

---
*Building the infrastructure for Real-World Asset tokenization on Solana.*
**Made with ❤️ in Pretoria, South Africa**

---
**Last Updated:** November 23, 2025
**Version:** 1.0
**Status:** Active Development
