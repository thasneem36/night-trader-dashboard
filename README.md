# Night Trader Dashboard

Live paper-trading dashboard for Night Trader, an automated paper-trading bot running on an Alpaca paper account.

**Open the dashboard:** https://thasneem36.github.io/night-trader-dashboard/20d6fb3c35778e6da6f8fdcf/

## What it shows
- Account equity, today's P&L and total P&L
- Open positions with entry, stop-loss and profit target
- Open risk used against the 6% cap
- A TradingView-style chart (Lightweight Charts) with candles, volume, SMA20/SMA50 and entry/stop/target lines
- The last 10 trades and the latest bot decisions with reasons
- A watchlist showing each symbol's trend versus its 50-day average

## How it updates
The bot checks the market every 10 minutes and republishes the data here afterward. Times are shown in Colombo time (UTC+5:30).

## Risk rules
- Max 2% risk per trade
- Max 6% total open risk
- A stop-loss on every trade
- Liquid markets only
- Paper trading only

This is paper trading with practice money. No API keys or secrets are stored in this repo.
