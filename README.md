MetaMask Deeplink Generator - README

⚡ Vibe-coded with gradient animations and smooth transitions

🎯 What This Does
A web-based tool that generates MetaMask deeplinks for four core functions:
🏠 Home

Generates simple https://link.metamask.io/home deeplinks
One-click QR code generation for mobile handoff

🔄 Swap

Cross-chain token swaps across 11 blockchains (Ethereum, Polygon, Base, Arbitrum, Optimism, Avalanche, BNB Chain, Linea, Solana, Bitcoin, Tron)
Live USD ↔ Crypto conversion using CoinGecko API (60-second cache)
200+ Ondo Finance tokenized stocks & ETFs (Apple, Tesla, NVIDIA, SPY, QQQ, etc.)
Automatically calculates base units for precise amounts
mUSD support (crypto-only mode, no USD conversion)
Smart token grouping (Base → Ondo Stocks → Ondo ETFs → Other)

💳 Buy

Generate on-ramp links for buying crypto
USD/Crypto toggle with live price conversion
Pre-fill chain, token, and amount parameters

🔮 Predict

Polymarket integration via Gamma API
Paste full Polymarket URL → auto-extracts market slug → fetches market ID
Fallback: Direct market ID entry
Real-time API feedback with loading states

🔧 Functionality

QR code generation for all deeplinks (mobile-ready)
Copy-to-clipboard with toast notifications
Reset buttons to clear all fields
Form validation with helpful error messages
Price caching (1-minute timeout to reduce API calls)

⚠️ Safety Features

Prominent signing warning (pulsing red box)
Links to official MetaMask signer: https://signer.link.metamask.consensys.io
Informational disclaimers about token verification and routing

🛠️ Tech Stack

Pure HTML/CSS/JavaScript (no frameworks, max compatibility)
QRCode.js library for QR generation
CoinGecko API for live crypto prices
Polymarket Gamma API for prediction market data
AllOrigins proxy for CORS handling

🚀 Usage

Select parameters (chain, token, amount)
Click Generate → deeplink appears
Copy or scan QR code → open in MetaMask mobile
⚠️ CRITICAL: Sign the deeplink before sharing/using

📋 Supported Assets

Ethereum: ETH, mUSD, USDC, USDT, DAI, WETH, WBTC + 200+ Ondo tokens
Polygon: POL, USDC, USDT, WETH
Base: ETH, USDC
Arbitrum: ETH, USDC, ARB
Optimism: ETH, USDC, OP
Avalanche: AVAX, USDC
BNB Chain: BNB, USDT
Linea: ETH, USDC
Solana: SOL, USDC, USDT
Bitcoin: BTC
Tron: TRX, USDT, USDC


Beta Version | Always test links before production use | Sign all deeplinks via official MetaMask signer
