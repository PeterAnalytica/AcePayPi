# AcePay Pi

**AcePay Pi** is a Pi-first merchant and payments capture app designed to feed clean,
structured transaction data into **AcePi** for accounting, tax, FX and chain intelligence.

It focuses on:

- Recording payments in **Pi, fiat and other crypto**
- Capturing key context:
  - Amount, currency, channel, chain
  - Basic tax country / business info
- Exporting a ready-made **AcePi payload JSON** so that:
  - AcePi can classify and post the entries
  - ACA Control Room can analyse them
  - Ace Insights can generate narratives and content

## Vision

AcePay Pi is the **front door** for hybrid payments in the Ace ecosystem:

- Pi Network payments at physical and online stores
- Traditional rails (bank transfer, card, POS)
- Exchange-based flows (Binance, Bybit, OKX, etc.)
- Web3 wallets (MetaMask, TON, etc.)

All unified into one data stream that AcePi understands.

## MVP (First Release)

- Browser-based web app (static, on GitHub Pages)
- Simple merchant-facing UI:
  - Add a payment
  - View current session payments
  - Download an **AcePi-ready JSON payload**
- No backend, no login in v1 — purely for data capture and export.

## Integration

- **AcePi** – consumes the exported JSON as input payload
- **ACA Control Room** – inspects the resulting AcePi output
- **Ace Insights** – turns the data into daily/weekly/monthly narratives, threads and reports
