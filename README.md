# Crypto Alert Automation & Web3 Dashboard

An automated system that monitors the Top 50 cryptocurrencies for volatility and trending status, sending alerts to Telegram and logging data to a Web3-styled dashboard.

## Tech Stack
- **Automation:** Make.com
- **Data Source:** CoinGecko API
- **Database:** Airtable
- **Backend:** Node.js / Express
- **Frontend:** JavaScript / Tailwind CSS (Neon Purple & Sand Theme)

## System Architecture
1. **Schedule:** Runs every 5 minutes.
2. **Fetch:** Pulls market data from CoinGecko.
3. **Logic:** Filters for price changes > 5% or Trending status.
4. **Alert:** Pings Telegram/Slack.
5. **Log:** Syncs data to Airtable.
6. **UI:** Displays live data on a Cyberpunk Dashboard.
