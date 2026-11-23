# Lumen Invest – Stock Market App (UI/UX)

Sqrock IT Solutions · UI/UX Internship · Phase 2 · Task 2

A mobile-first fintech app concept, delivered as a **clickable HTML/CSS/JS prototype** (single file, no build step). Open `index.html`; it renders inside a phone frame on desktop and full-screen on a phone.
Companies, tickers, prices and news are **fictional** (e.g. NOVA, KITE); no real market data and no real orders.

## Screens
1. **Splash / welcome** – logo, welcome message, finance-themed gradient background with live-market chip, Get Started
2. **Login** and **Signup** – email/mobile, password, continue, social login, forgot-password link
3. **Home dashboard** – search, market overview, trending stocks, top gainers, top losers, watchlist preview, news highlights, bottom navigation. Stock rows show logo, name, symbol, price, change and % change
4. **Stock details** – interactive price chart with Daily / Weekly / Monthly / Yearly ranges, market cap, volume, day and 52-week high/low, about, Add/Remove watchlist (★), Buy / Sell bottom sheet with quantity stepper and estimated total (UI concept)
5. **Portfolio** – total value, invested amount, profit & loss, performance chart, asset-allocation donut, holdings, transaction history
6. **Market news** – category chips, featured article, latest headlines
7. **Watchlist** – search, add and remove stocks (works live)
8. **Profile & settings** – profile, light/dark theme (works live), language, notification toggles, help & support, logout
9. **Design system** – colour, typography, buttons, chips, spacing

## Design decisions
- **Green/red are paired with ▲▼ and +/− signs** so gains and losses are readable without colour.
- Large, tabular price figures and one primary action per screen (Buy) keep beginner investors oriented; secondary details sit in cards.
- 8-pt spacing, 18 px card radius, 14 px control radius, 18 px screen padding, 44 px minimum touch targets.
- Light default (high legibility for numbers) with a full dark theme.

## Exports
`screens/` holds 2× PNG exports of all screens, the Yearly chart state, buy sheet, and dark-mode profile/home.

## Honest status
Code-built prototype, **not a Figma/XD file** (no design-tool access in the environment where it was made). Screens map one-to-one onto Figma frames and components.
