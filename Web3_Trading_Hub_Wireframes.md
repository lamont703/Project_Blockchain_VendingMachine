# Web3 Trading Hub - Complete Wireframes & Design Specifications

**Client:** Johnnie ("JHeat" on TikTok)  
**Project:** Blockchain-powered Digital Vending Machine for NFT Trading Cards

## 🎨 Design System

### Color Palette & Theme

- **Primary Yellow:** #FFD700 (Vending machine, CTAs)
- **Secondary Blue:** #87CEEB (Info sections, cards)
- **Accent Red:** #FF6347 (Alerts, special actions)
- **Base White:** #FFFFFF (Backgrounds)
- **Style:** Pokémon/Game Boy retro aesthetic with modern Web3 functionality

## 📱 Complete Screen Wireframes

### 1. LANDING PAGE - Desktop & Mobile

#### Desktop Layout (1200px+)

```
HEADER: [🎮 Web3 Trading Hub] [Home] [🛒 Marketplace] [How It Works] [🔗 Connect Wallet]

HERO SECTION:
┌─────────────────────────────────────────────────────────┐
│                🎰 DIGITAL VENDING MACHINE               │
│                   [Animated Pixel Art]                 │
│                                                         │
│  💰 $25 BASIC      💎 $50 PREMIUM      👑 $75 ELITE    │
│  ┌─────────────┐   ┌─────────────┐   ┌─────────────┐   │
│  │ 5 Cards     │   │ 10 Cards    │   │ 15 Cards    │   │
│  │             │   │ + 1 Rare    │   │ + Legendary │   │
│  │ [BUY NOW]   │   │ [BUY NOW]   │   │ [BUY NOW]   │   │
│  └─────────────┘   └─────────────┘   └─────────────┘   │
│                                                         │
│    💳 Credit Card Payment | 🔗 Connect Polygon Wallet  │
└─────────────────────────────────────────────────────────┘
```

#### Mobile Layout (320px-768px)

```
┌─────────────────────┐
│ [🍔] Web3 Trading   │
│      Hub            │
├─────────────────────┤
│   🎰 VENDING        │
│     MACHINE         │
│  [Hero Animation]   │
│                     │
│ ┌─────────────────┐ │
│ │ 💰 $25 BASIC    │ │
│ │ 5 Random Cards  │ │
│ │ [TAP TO BUY]    │ │
│ └─────────────────┘ │
│                     │
│ ┌─────────────────┐ │
│ │ 💎 $50 PREMIUM  │ │
│ │ 10 Cards + Rare │ │
│ │ [TAP TO BUY]    │ │
│ └─────────────────┘ │
│                     │
│ ┌─────────────────┐ │
│ │ 👑 $75 ELITE    │ │
│ │15 Cards + Legend│ │
│ │ [TAP TO BUY]    │ │
│ └─────────────────┘ │
└─────────────────────┘
```

### 2. PURCHASE FLOW WIREFRAMES

#### Payment Selection Modal

```
┌─────────────────────────────────┐
│        Choose Payment Method     │
├─────────────────────────────────┤
│                                 │
│ 💳 CREDIT CARD (Stripe)         │
│ ┌─────────────────────────────┐ │
│ │ ✓ Quick & Easy              │ │
│ │ ✓ No wallet needed          │ │
│ │ [CONTINUE WITH CARD] ────→  │ │
│ └─────────────────────────────┘ │
│                                 │
│ 🔗 POLYGON WALLET               │
│ ┌─────────────────────────────┐ │
│ │ ✓ Own NFTs instantly        │ │
│ │ ✓ Lower transaction fees    │ │
│ │ [CONNECT WALLET] ────────→  │ │
│ └─────────────────────────────┘ │
│                                 │
│           [❌ CANCEL]           │
└─────────────────────────────────┘
```

#### Minting Animation Screen

```
┌─────────────────────────────────┐
│      🎪 MINTING YOUR NFTS       │
├─────────────────────────────────┤
│                                 │
│         🎰 VENDING MACHINE      │
│           ┌─────────┐           │
│           │   🎁    │ ← Drop    │
│           │  PACK   │   anim    │
│           └─────────┘           │
│              │││                │
│            [VEND]               │
│                                 │
│   ⏳ Creating your random       │
│      NFT trading cards...       │
│                                 │
│    [████████░░] 80%             │
└─────────────────────────────────┘
```

#### Card Reveal Screen

```
┌─────────────────────────────────┐
│       🎉 CONGRATULATIONS!       │
├─────────────────────────────────┤
│                                 │
│      Your New NFT Cards:        │
│                                 │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ │
│ │ 🎨  │ │ 🎨  │ │ 🎨  │ │ 🎨  │ │
│ │Fire │ │Water│ │Grass│ │Elec │ │
│ │⭐ C │ │💎 R │ │⭐ C │ │👑 L │ │
│ └─────┘ └─────┘ └─────┘ └─────┘ │
│                                 │
│         [Flip animations]       │
│                                 │
│ [📱 VIEW COLLECTION] [🔄 BUY MORE] │
│         [🏠 RETURN HOME]        │
└─────────────────────────────────┘
```

### 3. USER DASHBOARD WIREFRAMES

#### Main Dashboard View

```
┌─────────────────────────────────────────────────────────┐
│ [👤 Profile] [🎨 Collection] [🛒 Marketplace] [🔥 Redeem] [⚙️ Settings] │
├─────────────────────────────────────────────────────────┤
│                                                         │
│ Welcome back, Trainer! 👋                              │
│                                                         │
│ ┌───────────────┐ ┌───────────────┐ ┌───────────────┐ │
│ │ 📊 TOTAL NFTS │ │ 💰 TOTAL SPENT│ │ 📦 REDEEMED   │ │
│ │      24       │ │     $150      │ │       3       │ │
│ └───────────────┘ └───────────────┘ └───────────────┘ │
│                                                         │
│ 🎨 Your NFT Collection (Grid View):                     │
│                                                         │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐       │
│ │ 🔥  │ │ 💧  │ │ 🌱  │ │ ⚡  │ │ 🌟  │ │ 🔮  │       │
│ │Fire │ │Water│ │Grass│ │Elec │ │Light│ │Dark │       │
│ │⭐ C │ │💎 R │ │⭐ C │ │👑 L │ │💎 R │ │⭐ C │       │
│ │🔥Burn│ │🔥Burn│ │🔥Burn│ │🔥Burn│ │🔥Burn│ │🔥Burn│       │
│ └─────┘ └─────┘ └─────┘ └─────┘ └─────┘ └─────┘       │
│                                                         │
│ [Show More...] [🔄 Buy New Packs] [📤 Share Collection]│
└─────────────────────────────────────────────────────────┘
```

#### Redemption Flow

```
┌─────────────────────────────────┐
│      🔥 BURN & REDEEM CARD      │
├─────────────────────────────────┤
│                                 │
│ Selected NFT:                   │
│ ┌─────────────────────────────┐ │
│ │ 🔥 Charizard Elite #0042    │ │
│ │ 👑 Legendary Tier           │ │
│ │ ⭐ Rarity Score: 95/100     │ │
│ └─────────────────────────────┘ │
│                                 │
│ ⚠️  WARNING: This action will   │
│     permanently BURN your NFT!  │
│                                 │
│ 📝 Shipping Information:        │
│ ┌─────────────────────────────┐ │
│ │ Full Name: [_______________] │ │
│ │ Address: [_________________] │ │
│ │ City: [___________________] │ │
│ │ State: [▼ Select State]     │ │
│ │ ZIP Code: [_______________] │ │
│ │ Phone: [_________________] │ │
│ └─────────────────────────────┘ │
│                                 │
│ Estimated Delivery: 7-14 days   │
│                                 │
│ [🔥 CONFIRM BURN] [❌ CANCEL]   │
└─────────────────────────────────┘
```

### 4. MARKETPLACE WIREFRAMES

#### Marketplace Browse View

```
┌─────────────────────────────────────────────────────────┐
│ [🔍 Search] [🎯 Filter] [📊 Sort] [🛒 My Listings] [💰 Sell]│
├─────────────────────────────────────────────────────────┤
│                                                         │
│ 🛒 Trading Card Marketplace                             │
│                                                         │
│ Quick Filters:                                          │
│ [⭐ Common] [💎 Rare] [👑 Epic] [🌟 Legendary] [🔥 Hot]│
│                                                         │
│ 📊 Featured Cards:                                      │
│ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐ ┌─────┐ │
│ │ 🔥 Charizard│ │ 💧 Blastoise│ │ 🌱 Venusaur │ │ ⚡ P │ │
│ │ #1337       │ │ #0042       │ │ #0889       │ │ #025 │ │
│ │ 👑 Legendary│ │ 💎 Rare     │ │ 👑 Epic     │ │ 💎 R │ │
│ │ 💰 $89.99   │ │ 💰 $24.99   │ │ 💰 $45.99   │ │ 💰 $│ │
│ │ [📤 SELL]   │ │ [💰 BUY]    │ │ [🔄 TRADE]  │ │ [💰]│ │
│ └─────────────┘ └─────────────┘ └─────────────┘ └─────┘ │
│                                                         │
│ 🔥 Recently Listed:                                     │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ 🎨 Pikachu Shiny #0025 | 💎 Rare | 💰 $19.99      │ │
│ │ 🎨 Mewtwo Dark #0150   | 🌟 Legendary | 💰 $125.00 │ │
│ │ 🎨 Gyarados Blue #0130 | 👑 Epic | 💰 $67.50       │ │
│ │ 🎨 Dragonite Gold #149 | 👑 Epic | 💰 $55.00       │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ [Show More...] [📈 View Market Stats] [🔔 Price Alerts] │
└─────────────────────────────────────────────────────────┘
```

#### Individual Card Listing View

```
┌─────────────────────────────────────────────────────────┐
│ [← Back to Marketplace] [🔖 Bookmark] [📤 Share] [⚠️ Report]│
├─────────────────────────────────────────────────────────┤
│                                                         │
│ Card Details:                                           │
│ ┌─────────────┐ ┌─────────────────────────────────────┐ │
│ │             │ │ 🔥 Charizard Elite Edition #1337   │ │
│ │     🎨      │ │ 👑 Legendary Tier                   │ │
│ │  [Card Art] │ │ ⭐ Rarity Score: 95/100             │ │
│ │             │ │ 🔥 Element: Fire                    │ │
│ │   [3D View] │ │ ⚡ Power Level: 95/100              │ │
│ └─────────────┘ │ 🏷️ Generation: Gen 1                │ │
│                 │ 🎯 Special: Dragon Breath           │ │
│ 💰 Current Price: $89.99                               │ │
│ 📊 Price History: [Chart shows $45→$67→$89]           │ │
│                                                         │ │
│ 👤 Seller: TrainerAsh2024                              │ │
│ ⭐ Rating: 4.8/5 (47 trades)                           │ │
│ 🏆 Verified Seller Badge                               │ │
│                                                         │ │
│ 📝 Description:                                        │ │
│ "Mint condition Charizard from premium pack.           │ │
│  Perfect for collectors. Quick sale needed!"           │ │
│                                                         │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ [💰 BUY NOW] [🔄 MAKE OFFER] [📞 CONTACT SELLER]      │
└─────────────────────────────────────────────────────────┘
```

#### Sell Card Interface

```
┌─────────────────────────────────────────────────────────┐
│                   💰 SELL YOUR CARD                     │
├─────────────────────────────────────────────────────────┤
│                                                         │
│ Select Card to Sell:                                    │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ My Collection:                                      │ │
│ │ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐   │ │
│ │ │ 🔥  │ │ 💧  │ │ 🌱  │ │ ⚡  │ │ 🌟  │ │ 🔮  │   │ │
│ │ │Fire │ │Water│ │Grass│ │Elec │ │Light│ │Dark │   │ │
│ │ │⭐ C │ │💎 R │ │⭐ C │ │👑 L │ │💎 R │ │⭐ C │   │ │
│ │ │✓SEL │ │     │ │     │ │     │ │     │ │     │   │ │
│ │ └─────┘ └─────┘ └─────┘ └─────┘ └─────┘ └─────┘   │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ Selected: 🔥 Fire Dragon #0042                          │
│ Market Value: $45.99 (Recent sales: $42-$48)           │
│                                                         │
│ 💰 Pricing Options:                                     │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ ● Fixed Price: $[___] (Instant sale)                │ │
│ │ ○ Auction: Start $[___] Duration: [7 days ▼]        │ │
│ │ ○ Best Offer: Min $[___] (Accept offers)            │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 📝 Listing Details:                                     │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ Title: [Fire Dragon - Mint Condition]               │ │
│ │ Description: [Rare card from premium pack...]       │ │
│ │ Tags: [fire] [dragon] [rare] [mint]                 │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 🔒 Transaction Fee: 2.5% (≈$1.15)                      │
│ 💰 You'll Receive: $44.84                              │
│                                                         │
│ [📤 LIST FOR SALE] [💾 SAVE DRAFT] [❌ CANCEL]         │
└─────────────────────────────────────────────────────────┘
```

#### Trading Interface

```
┌─────────────────────────────────────────────────────────┐
│                   🔄 TRADE CARDS                        │
├─────────────────────────────────────────────────────────┤
│                                                         │
│ Trading with: TrainerBlue87 ⭐ (4.6/5 rating)          │
│                                                         │
│ ┌─────────────────────┐ ┌─────────────────────────────┐ │
│ │    YOUR OFFER       │ │    THEIR OFFER              │ │
│ │ ┌─────┐ ┌─────┐     │ │ ┌─────┐ ┌─────┐ ┌─────┐   │ │
│ │ │ 🔥  │ │ 💧  │     │ │ │ ⚡  │ │ 🌟  │ │ 🔮  │   │ │
│ │ │Fire │ │Water│     │ │ │Elec │ │Light│ │Dark │   │ │
│ │ │💎 R │ │⭐ C │     │ │ │👑 L │ │💎 R │ │⭐ C │   │ │
│ │ │$25  │ │$12  │     │ │ │$89  │ │$45  │ │$8   │   │ │
│ │ └─────┘ └─────┘     │ │ └─────┘ └─────┘ └─────┘   │ │
│ │                     │ │                           │ │
│ │ Total Value: $37    │ │ Total Value: $142         │ │
│ │ [+ Add Cards]       │ │ [+ Request Cards]         │ │
│ │ [+ Add MATIC]       │ │ [+ Add MATIC]             │ │
│ └─────────────────────┘ └─────────────────────────────┘ │
│                                                         │
│ 📝 Trade Notes:                                         │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ "Looking for legendary electric types! Happy to     │ │
│ │  add extra MATIC to balance the trade."             │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ ⚖️ Trade Balance: You need +$105 value or extra MATIC   │
│                                                         │
│ [🔄 PROPOSE TRADE] [💬 SEND MESSAGE] [❌ CANCEL]       │
└─────────────────────────────────────────────────────────┘
```

#### My Marketplace Activity

```
┌─────────────────────────────────────────────────────────┐
│ [📤 My Listings] [📥 My Purchases] [🔄 Trade History] [💰 Earnings]│
├─────────────────────────────────────────────────────────┤
│                                                         │
│ 📤 Active Listings (3):                                │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ 🔥 Charizard #1337 | 💰 $89.99 | 👁️ 24 views      │ │
│ │ 💧 Blastoise #0009 | 💰 $34.99 | 👁️ 8 views       │ │
│ │ 🌱 Venusaur #0003  | 💰 $42.50 | 👁️ 12 views      │ │
│ │ [Edit] [Remove] [Boost] [Stats] for each listing    │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 🔔 Recent Activity:                                     │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ ✅ SOLD: Pikachu #0025 for $19.99 (2 hours ago)    │ │
│ │ 💰 OFFER: $15.00 on your Squirtle #0007             │ │
│ │ 🔄 TRADE: Proposed trade for your Mewtwo #0150      │ │
│ │ 👁️ VIEWED: 5 new views on Charizard #1337          │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 📊 Performance Stats:                                   │
│ ┌───────────────┐ ┌───────────────┐ ┌───────────────┐ │
│ │ 💰 TOTAL EARNED│ │ 🎯 SUCCESS RATE│ │ ⭐ RATING     │ │
│ │    $247.50     │ │      87%       │ │   4.8/5      │ │
│ └───────────────┘ └───────────────┘ └───────────────┘ │
│                                                         │
│ [📈 Detailed Analytics] [🎯 Pricing Assistant] [🔔 Alerts]│
└─────────────────────────────────────────────────────────┘
```

### 5. ADMIN PORTAL WIREFRAMES

#### Admin Dashboard Overview

```
┌─────────────────────────────────────────────────────────┐
│ [🔐 Admin] [🎨 NFT Mgmt] [🛒 Marketplace] [📊 Analytics] [👥 Users] [⚙️] │
├─────────────────────────────────────────────────────────┤
│                                                         │
│ 📊 Platform Statistics:                                 │
│ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐ ┌─────┐ │
│ │💰 REVENUE   │ │🎁 PACKS SOLD│ │👥 TOTAL USERS│ │🛒 MKT│ │
│ │   $2,500    │ │     75      │ │      45      │ │ 234 │ │
│ └─────────────┘ └─────────────┘ └─────────────┘ └─────┘ │
│                                                         │
│ 🎨 NFT Management Panel:                                │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ [➕ MINT NEW NFT] [📁 BATCH UPLOAD] [🎰 ASSIGN TIER]│ │
│ │ [📊 VIEW INVENTORY] [🔍 SEARCH NFTS] [⚙️ SETTINGS] │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 🎰 Vending Machine Inventory Status:                    │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────┐ │
│ │ TIER 1 ($25)    │ │ TIER 2 ($50)    │ │ TIER 3 ($75)│ │
│ │ ✅ 50 Available │ │ ⚠️  30 Available │ │ 🔴 10 Available│ │
│ │ [MANAGE TIER]   │ │ [MANAGE TIER]   │ │ [MANAGE TIER]│ │
│ └─────────────────┘ └─────────────────┘ └─────────────┘ │
│                                                         │
│ 📦 Recent Redemption Requests:                          │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ User: john@email │ Card: Charizard #42 │ [FULFILL] │ │
│ │ User: jane@email │ Card: Pikachu #18   │ [SHIPPED] │ │
│ │ User: bob@email  │ Card: Blastoise #7  │ ✅ DONE   │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 🛒 Marketplace Management:                              │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ 🏷️ Active Listings: 234 | 💰 Total Volume: $45,230 │ │
│ │ 🔄 Pending Trades: 12   | ⚠️ Disputed: 2           │ │
│ │ 📊 Commission Earned: $1,130.75 (2.5% fee)         │ │
│ │ [Manage Listings] [Review Disputes] [Set Fees]      │ │
│ └─────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────┘
```

#### NFT Creation Interface

```
┌─────────────────────────────────────────────────────────┐
│                   🎨 CREATE NEW NFT                     │
├─────────────────────────────────────────────────────────┤
│                                                         │
│ 📁 Artwork Upload:                                      │
│ ┌─────────────────────────────────────────────────────┐ │
│ │     [📎 Drop image files here or click to browse]   │ │
│ │              Supported: PNG, JPG, GIF               │ │
│ │              Maximum size: 10MB per file            │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ 📝 NFT Metadata & Properties:                           │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ Card Name: [Charizard Elite Edition]                │ │
│ │ Description: [Epic fire-type dragon with...]        │ │
│ │                                                     │ │
│ │ Rarity Level: [▼ Select Rarity]                     │ │
│ │   ⭐ Common | 💎 Rare | 👑 Epic | 🌟 Legendary      │ │
│ │                                                     │ │
│ │ Tier Assignment: [▼ Select Tier]                    │ │
│ │   $25 Basic | $50 Premium | $75 Elite               │ │
│ │                                                     │ │
│ │ Custom Attributes:                                  │ │
│ │ • Element Type: [Fire ▼]                           │ │
│ │ • Power Level: [95/100 ─────●───]                  │ │
│ │ • Generation: [Gen 1 ▼]                            │ │
│ │ • Special Ability: [Dragon Breath]                 │ │
│ │ [+ Add New Attribute]                              │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│ ⚙️ Minting Configuration:                               │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ Quantity to Mint: [1] ← (Individual unique NFTs)   │ │
│ │ ☑️ Upload metadata to IPFS                         │ │
│ │ ☑️ Add to vending machine inventory                 │ │
│ │ ☑️ Enable physical redemption                       │ │
│ └─────────────────────────────────────────────────────┘ │
│                                                         │
│          [🎨 MINT NFT] [📋 SAVE DRAFT] [❌ CANCEL]      │
└─────────────────────────────────────────────────────────┘
```

## 🔧 Technical Implementation Specifications

### Responsive Breakpoints

- **Mobile First:** 320px - 768px (vertical stack)
- **Tablet:** 768px - 1024px (2-column hybrid)
- **Desktop:** 1024px+ (3-column grid)

### Key Animations & Interactions

1. **Vending Machine Drop:** CSS physics-based falling animation
2. **Card Flip Reveal:** 3D CSS transforms with stagger effect
3. **Pack Opening:** Sequential card reveals with celebration
4. **Loading States:** Retro progress bars with pixel aesthetics

### Web3 Integration Points

- **Polygon Network:** Low-cost NFT minting and transactions
- **IPFS Storage:** Decentralized metadata and image hosting
- **Wallet Connect:** Support for MetaMask, WalletConnect, Coinbase
- **Smart Contracts:** ERC-721 with burn functionality for redemption

### Payment Processing

- **Stripe Integration:** Credit card payments for non-crypto users
- **Polygon Transactions:** Direct wallet payments with MATIC
- **Email Escrow:** Temporary NFT storage for guest purchases

## 🎯 User Experience Flows Summary

### Flow A: Guest Purchase (Credit Card)

Landing → Select Tier → Credit Card → Email → Mint → Store in Backend → Prompt Login

### Flow B: Wallet Purchase (Crypto Native)

Landing → Connect Wallet → Select Tier → Approve TX → Mint to Wallet → Dashboard

### Flow C: NFT Redemption

Dashboard → Select NFT → Burn Warning → Shipping Form → Confirm → Admin Fulfillment

### Flow D: Admin Management

Secure Login → Dashboard → Mint NFTs → Assign Tiers → Monitor Sales → Handle Redemptions

### Flow E: Marketplace Trading

Dashboard → Marketplace → Browse/Search → Select Card → Buy/Offer/Trade → Complete Transaction

### Flow F: Selling Cards

Dashboard → My Collection → Select Card → List for Sale → Set Price → Manage Listing → Complete Sale

### Flow G: P2P Trading

Dashboard → Marketplace → Find Trade Partner → Propose Trade → Negotiate → Execute Trade

---

_This comprehensive wireframe specification provides the complete foundation for developing the Web3 Trading Hub platform with its retro gaming aesthetic and modern blockchain functionality._
