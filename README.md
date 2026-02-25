# BTC/USDT Grid Trading Bot (Binance Testnet)

Professional proof-of-concept grid trading bot designed for investor pitch.

## Strategy
- **Type:** Neutral Grid Trading
- **Pair:** BTC/USDT
- **Levels:** 12 grid levels
- **Spacing:** 1.18% (~$802.02)
- **Bounds:** $63,452.26 - $72,274.50
- **Stop-Loss:** $57,107 (10% below grid floor)

## Technical Highlights
- **Architecture:** Serverless autonomous workflow with 5-minute cycles.
- **Authentication:** Custom HMAC-SHA256 signature generation.
- **Communication:** Clean REST API integration using curl-based POST requests.
- **Reliability:** Implements recvWindow=60000 and server time offset synchronization.

## Setup & Configuration
- Configuration is managed via config.json.
- Uses Binance Testnet API keys for safe proof-of-concept demonstration.

## Monitoring
- Real-time logging to Google Sheets trade log.
- Live dashboard via Twin Agent Interface.
- Daily P&L email reports.
