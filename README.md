# SplitEase — Expense Splitter

A clean, premium expense splitter web app for personal use, friend groups, and work outings.

## Features

- **Event-based splitting** — every expense lives inside a named trip or event
- **Category tagging** — food, hotel, fuel, transport, drinks, and more
- **Equal split** — automatic equal split across all participants
- **Visual balances** — see who's up and who owes at a glance
- **Minimum settlements** — calculates the fewest transactions needed to settle up
- **WhatsApp export** — emoji-rich formatted summary, paste-ready
- **PDF download** — full invoice-style report with 4 tables (expenses, categories, balances, settlements)
- **Trip History** — save completed trips to localStorage, view category breakdown and per-head cost
- **Reuse trips** — reload past trips with the same people for repeat outings
- **Works offline** — no login, no server, everything stored locally

## Tech Stack

- Vanilla HTML / CSS / JavaScript — zero frameworks, zero dependencies
- [jsPDF](https://github.com/parallax/jsPDF) + [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) for PDF generation (via CDN)
- Google Fonts — Playfair Display + Syne
- localStorage for trip history persistence

## Deployment

Deployed via [Vercel](https://vercel.com) — just connect the repo and it's live instantly.

## Part of rohansvibe apps

Companion app to the [Fuel Trip Calculator](https://fuel-calculator-beta.vercel.app).
