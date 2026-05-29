# Trading Alerts & Predictions Dashboard 📈

A real-time crypto and forex trading alerts dashboard with arbitrage 
detection, cross-exchange execution, and portfolio management — built 
with TypeScript and React.

## 🚀 Features

### Arbitrage Engine
- Detects cross-exchange arbitrage opportunities in real time
- Supports Binance, Coinbase, Kraken, London FX and more
- Clickable toggles to link/unlink exchange API bridges
- Tracks accumulated yield and profit metrics per opportunity

### Bridge API Handshake
- Sub-second authorization flow for disconnected exchanges
- Sequential automated handshaking phases:
  - Negotiating API credentials
  - Synchronizing order books
  - Establishing trade connectivity

### Portfolio & Wallet
- Direct wallet settlement — arbitrage profits credited in real time
- USD Portfolio Wallet balance updated on each execution
- Full traceable ledger of all arbitrage transactions
  (e.g. "Arbitrage Yield via Binance → Bybit")

### Market Grid & Alerts
- Live asset detail panels with market grid view
- Alert panel for triggered trading signals
- Wallet panel for balance and settlement tracking

## 🛠️ Tech Stack
- **Language:** TypeScript
- **Frontend:** React + Vite
- **Animations:** Motion/React + AnimatePresence
- **Icons:** Lucide React
- **Backend:** Node.js (server.ts)

## ⚙️ Setup
```bash
npm install
cp .env.example .env
# Add your API keys to .env
npm run dev
```

## 🔗 Related Projects
- [gifttocash-backend](https://github.com/nemzco-pixel/gifttocash-backend)
- [gifttocash-frontend](https://github.com/nemzco-pixel/gifttocash-frontend)
