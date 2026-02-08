# 📊 Qullamaggie Trading System

A comprehensive swing trading command center built around **Kristjan Kullamägi's (Qullamaggie)** exact trading methodology.

![License](https://img.shields.io/badge/license-MIT-blue)
![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-green)

## 🚀 Live Demo

After deploying, your app will be live at: `https://<your-username>.github.io/<repo-name>/`

## Features

### 🔍 AI Setup Scanner
- Enter any US stock ticker for AI-powered analysis
- Grades stocks against Qullamaggie's exact 6-point checklist
- Identifies setup type: **Breakout/HTF**, **Episodic Pivot**, or **Parabolic Short**
- Shows EMA positions, breakout pivots, stop levels, and catalysts
- Requires an Anthropic API key (stored locally in your browser)

### 🎯 Trade Planner
- Position sizing using QM's formula: `Position Size = Risk $ / (Entry − Stop)`
- Warns if stop exceeds ADR% (a core QM rule)
- R-multiple target calculator with partial sell levels
- All 3 setup types with Kristjan's exact rules displayed

### 📓 Trade Journal
- Log trades with R-multiple tracking
- Equity curve charted in R-multiples (not just $)
- R-distribution histogram
- Per-setup performance breakdown (Breakout vs EP vs Parabolic)

### 📚 Study Lab
- Qullamaggie's stock selection process (3-step method)
- All 3 setups as quick-reference cards
- Rotating carousel of Kristjan's actual quotes & wisdom
- Chart study database builder (he studied thousands of winners—you should too)

## 🛠️ Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it something like `qullamaggie-trading-system`
3. Set it to **Public**
4. Click **Create repository**

### Step 2: Upload the Files
**Option A — Upload via GitHub UI:**
1. Click **"uploading an existing file"** on the repo page
2. Drag and drop `index.html` and this `README.md`
3. Click **Commit changes**

**Option B — Using Git CLI:**
```bash
git clone https://github.com/<your-username>/qullamaggie-trading-system.git
cd qullamaggie-trading-system
# Copy index.html and README.md into this folder
git add .
git commit -m "Initial commit"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes, then visit `https://<your-username>.github.io/qullamaggie-trading-system/`

## 🔑 API Key Setup

The AI Scanner tab requires an **Anthropic API key** to function:
1. Get your key at [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. Enter it when prompted in the app
3. Your key is stored **only in your browser's localStorage** — never sent to any server except Anthropic's API directly

> ⚠️ The Trade Planner, Journal, and Study Lab tabs work fully without an API key.

## 📖 Qullamaggie's Core Principles

This app is built around these key concepts from Kristjan's public teachings:

- **Staircase movement**: Stocks move up → consolidate → move up again
- **3 setups**: Breakouts (HTF), Episodic Pivots, Parabolic Shorts
- **Position sizing**: Risk 0.25-1% per trade, stop ≤ ADR%
- **Management**: Sell ⅓-½ after 3-5 days, trail rest with 10/20 EMA
- **Win rate ~25%**: The edge is in R-multiples, not win rate
- **Study obsessively**: Build a database of winning patterns across decades

## ⚠️ Disclaimer

This tool is for **educational purposes only** and is **not financial advice**. Past performance does not guarantee future results. Trading involves substantial risk of loss. Always do your own research and consider consulting a financial advisor.

## License

MIT
