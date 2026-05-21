# Predictions Tracker

A browser-based investigation tool for tracking prediction market activity by wallet address. Built to support investigations into complex position and settlement issues on prediction markets that are difficult to trace through standard blockchain explorers.

---

## The Problem

Prediction market transactions involve protocol-specific data that standard blockchain explorers don't surface clearly. Positions, trades, settlements, and redemptions all live within Polymarket's own data model — and when a user reports a missing position or unexpected outcome, you need to see their full activity history within the protocol to understand what happened.

---

## Features

- Full market position history for a wallet address
- Trade activity: buys, sells, and redemptions with timestamps and amounts
- Position outcomes and settlement data
- Active and resolved market positions at a glance
- Clean, readable layout designed for quick scanning during a support investigation

---

## Stack

- **JavaScript** — core logic and API integration
- **HTML / CSS** — frontend interface
- **Polymarket API** — prediction market data source

---

## Notes

This is an internal tool and the live environment is not publicly accessible. Source code is not included as it contains environment-specific configurations. This README documents the project's purpose, design, and impact.
