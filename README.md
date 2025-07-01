# 🎮 Web3 Trading Hub

> A blockchain-powered digital vending machine for NFT trading cards with physical redemption capabilities

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Polygon](https://img.shields.io/badge/Blockchain-Polygon-8247E5)](https://polygon.technology/)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-3178C6)](https://www.typescriptlang.org/)

## 📖 Project Overview

Web3 Trading Hub is an innovative platform that brings the nostalgic experience of trading card packs into the Web3 era. Users can purchase randomized NFT trading card packs through a stylized vending machine interface and optionally redeem their digital cards for physical copies.

**Client:** Johnnie (aka "JHeat" on TikTok)  
**Theme:** Pokémon/Game Boy retro aesthetic  
**Network:** Polygon (MATIC) for low-cost transactions

## ✨ Key Features

### 🎰 Digital Vending Machine

- Retro gaming interface with pixel-art animations
- Three tier system: $25 Basic / $50 Premium / $75 Elite packs
- Flexible payment: Credit cards (Stripe) or crypto wallets
- Guest purchases without wallet connection

### 🎪 Minting & Reveal Experience

- Animated pack opening with physics-based drops
- 3D card flip reveals with rarity indicators
- Random algorithmic card generation
- Instant wallet minting for crypto users

### 👤 User Dashboard

- Collection management and viewing
- Burn & redeem for physical copies
- Shipping tracking and status updates
- Multi-wallet support (MetaMask, WalletConnect)

### 🔐 Admin Portal

- NFT creation with artwork upload
- Inventory management per tier
- Analytics dashboard for sales tracking
- Physical fulfillment workflow management

## 🛠 Tech Stack

- **Frontend:** React 18+ with TypeScript, Tailwind CSS
- **Blockchain:** Polygon (MATIC), ERC-721/1155 NFTs
- **Storage:** IPFS for decentralized metadata
- **Payments:** Stripe (credit cards) + native crypto
- **Backend:** Node.js/Next.js with Express
- **Authentication:** Web3 wallets + Magic.link for email

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- MetaMask browser extension
- Polygon testnet MATIC tokens

### Installation

```bash
# Clone repository
git clone https://github.com/your-org/web3-trading-hub.git
cd web3-trading-hub

# Install dependencies
npm install

# Setup environment
cp .env.example .env.local
# Configure your .env.local with API keys

# Setup database
npx prisma generate
npx prisma db push

# Start development server
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to see the application.

## 📁 Project Structure

```
web3-trading-hub/
├── components/          # React components
│   ├── VendingMachine/ # Main interface
│   ├── Dashboard/      # User dashboard
│   └── Admin/          # Admin portal
├── contracts/          # Smart contracts
├── pages/              # Next.js pages
├── lib/               # Utilities and configs
├── styles/            # Global styles
└── docs/              # Documentation
```

## 🎨 Design System

- **Primary Yellow:** `#FFD700` - CTAs and highlights
- **Secondary Blue:** `#87CEEB` - Information sections
- **Accent Red:** `#FF6347` - Alerts and special actions
- **Base White:** `#FFFFFF` - Backgrounds

## 🔄 User Flows

1. **Guest Purchase:** Landing → Tier → Payment → Email → Mint
2. **Wallet Purchase:** Landing → Connect → Tier → Transaction
3. **NFT Redemption:** Dashboard → Select → Burn → Ship
4. **Admin Management:** Login → Mint → Assign → Fulfill

## 📚 Documentation

- **[Complete Wireframes & Specs](./Web3_Trading_Hub_Wireframes.md)**
- **[Smart Contract Docs](./docs/contracts.md)**
- **[API Documentation](./docs/api.md)**
- **[Deployment Guide](./docs/deployment.md)**

## 🧪 Testing

```bash
npm test              # Unit tests
npm run test:contracts # Smart contract tests
npm run test:e2e      # End-to-end tests
```

## 🚀 Deployment

```bash
# Staging
npm run deploy:staging

# Production
npm run build
npm run deploy:mainnet
vercel --prod
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/name`)
3. Make changes and write tests
4. Commit (`git commit -m 'Add feature'`)
5. Push and open Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Client:** Johnnie ("JHeat") for the innovative vision
- **Inspiration:** Pokémon TCG and retro gaming aesthetics
- **Community:** Polygon and Web3 ecosystem

---

**Built with ❤️ for the Web3 community**

_Bringing nostalgic trading card experiences to the blockchain_
