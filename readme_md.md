# ⚡ Compare Your Mutual Fund

**Compare Your Mutual Fund** is a modern, high-performance financial research platform built specifically for the Indian mutual fund market. Designed with a sleek Gen-Z dark fintech aesthetic, it helps retail investors discover, evaluate, and compare SEBI-registered direct mutual funds based on their financial goals, risk appetite, and investment horizons.

---

## ✨ Key Features

1. **Algorithmic Investor Risk Scoring:** A 6-step psychological and financial questionnaire assesses user reactions to market drawdowns, target return expectations, and recurring monthly SIP amounts. It dynamically classifies investors into Conservative, Moderate, or Aggressive profiles using a weighted scoring model.
2. **Real-Time Interactive NAV Graphs:** Features custom-built vector SVG trajectory charts mapping fund growth from inception date directly to today. Includes timeframe selectors (`1Y`, `3Y`, `5Y`, `ALL`) and hover tooltips for precise date-stamped NAV valuation.
3. **Side-by-Side Comparison Matrix:** Compare up to 5 mutual funds simultaneously across 15+ quantitative parameters—including CAGR returns, Expense Ratios, Portfolio P/E ratios, Asset Allocations (Equity vs. Debt vs. Cash), Sharpe Ratios, Alphas, Betas, and Exit Loads.
4. **Beginner Micro-Explanations:** Complex financial jargon like Portfolio P/E, Standard Deviation, Sharpe Ratio, and Maximum Drawdown are paired with crisp 5-to-6 word micro-explanations.
5. **Live AMFI Auto-Sync Feeds:** Includes live timestamping and auto-update simulations reflecting daily NAV updates and Indian tax regulations.

---

## 🛠️ Technology Stack

- **Frontend:** React 18, JSX, Tailwind CSS
- **Icons & Visuals:** Lucide React, Custom SVG Charting Engine
- **Build Tool:** Vite
- **Deployment:** GitHub Actions & GitHub Pages

---

## 🚀 Quick Start (Local Setup)

Follow these steps to run the platform locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/compare-your-mutual-fund.git
   cd compare-your-mutual-fund
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to `http://localhost:5173` in your web browser.

---

## 📦 Deployment to GitHub Pages

### Automated Deployment (GitHub Actions)
1. Push your code to your `main` branch on GitHub:
   ```bash
   git add .
   git commit -m "Deploy platform"
   git push origin main
   ```
2. Go to your repository settings on GitHub: **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select the `gh-pages` branch and click **Save**.

### Manual Deployment Command
You can also deploy directly from your terminal using `gh-pages`:
```bash
npm run deploy
```

---

## ⚠️ Financial Disclaimer

Mutual fund investments are subject to market risks. Read all scheme related documents carefully. Past performance does not guarantee future returns. Recommendations are generated algorithmically based on user preferences and should not be considered formal SEBI-registered investment advice.

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).