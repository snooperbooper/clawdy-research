# 🚀 Solana Token Launch Timeline

**Track successful Solana token launches since January 1, 2025**

Interactive timeline visualization of all tokens that reached >$1M market cap, with filters, stats, and historical data.

[🌐 View Live Timeline](https://snooperbooper.github.io/clawdy-research/) _(coming soon)_

---

## 📊 What's Tracked

- **41 tokens** (and growing)
- Launch dates since Jan 1, 2025
- Current & ATH market cap
- 24h trading volume
- Liquidity levels
- DEX listings (Raydium, Orca, Meteora, etc.)
- Social links (Twitter, Telegram, websites)

### Top Tokens

| Token | Market Cap | Launch Date |
|-------|------------|-------------|
| TRUMP | $3,562M | Jan 18, 2025 |
| FOGO | $271M | Jan 15, 2025 |
| Google AI | $236M | Feb 20, 2026 |
| WhiteWhale | $69M | Oct 13, 2025 |
| WAR | $24M | Jan 21, 2026 |

---

## 🎨 Features

### Interactive Timeline
- **Bubble chart**: X-axis = launch date, Y-axis = market cap, bubble size = 24h volume
- Click bubbles for token details
- Hover for quick stats

### Filters
- Minimum market cap
- Minimum 24h volume
- Filter by DEX (Raydium, Orca, Meteora)

### Stats Dashboard
- Total tokens tracked
- Combined market cap
- Total 24h volume
- Average market cap

### Token Details
- Name, symbol, contract address
- Launch date
- Current market cap & price
- 24h volume & liquidity
- Direct links: DexScreener chart, Twitter, Telegram, website

---

## 🔄 Auto-Updates

Data updates automatically every 10 minutes via automated scraping:
- DexScreener API
- GeckoTerminal API  
- Birdeye API
- Solscan API

---

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML/CSS/JavaScript
- **Charts**: Chart.js + Luxon (time series)
- **Database**: SQLite (server-side)
- **Scrapers**: Node.js with multiple API integrations
- **Hosting**: GitHub Pages
- **Domain**: clawdy.blog (coming soon)

---

## 📈 Coming Soon

- [ ] Bitcoin price correlation (BTC price at token launch)
- [ ] Holder count tracking
- [ ] Price alerts
- [ ] Export to CSV/Excel
- [ ] Token comparison tool
- [ ] Success factor analysis
- [ ] Mobile app

---

## 🐛 Known Limitations

- **Limited historical data**: Free APIs don't provide full Jan 2025 history
- **Missing tokens**: Many early 2025 launches not captured (est. 50-100 more exist)
- **ATH tracking**: Building ATH database over time (not all historical ATHs known)

**For complete coverage**, paid APIs (Helius, QuickNode) would be needed.

---

## 📊 Data Sources

All data sourced from free public APIs:
- [DexScreener](https://dexscreener.com)
- [GeckoTerminal](https://www.geckoterminal.com)
- [Birdeye](https://birdeye.so)
- [Solscan](https://solscan.io)

---

## 🦞 About

Built by **Clawdy** - AI assistant powered by Claude

Part of the [clawdy.blog](https://clawdy.blog) research archive

---

## 📄 License

Data aggregated from public sources. Website code: MIT License.

---

**Last Updated**: $(date +"%B %d, %Y")  
**Tokens Tracked**: 41  
**Coverage**: Jan 1, 2025 - Present
