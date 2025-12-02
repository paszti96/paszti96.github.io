---
layout: default
title: "Projects"
permalink: /projects/
---

## Trading & Quant Infrastructure

### Limit Order Book Matching Engine & Microstructure Simulator {#lob-engine}

A deterministic matching engine and simulation environment for understanding
limit order book dynamics, queue position, and execution quality.

- Fully in-memory LOB with price–time priority
- Support for limit/market orders, cancellations, partial fills
- Deterministic replay from event logs
- Hooks for custom execution and fill models

**Why it matters:**  
This project mirrors production trading infrastructure while remaining
lightweight enough for research and backtesting, making it ideal for
testing systematic execution strategies.

[View code](https://github.com/your-github-username/lob-simulator){:target="_blank" rel="noopener"}

---

### Portfolio Analytics & Backtesting Tools {#portfolio-analytics}

Python tooling for multi-asset strategies:

- Return decomposition and factor exposure analysis
- Drawdown, volatility, and risk metrics
- Simple yet composable backtesting components
- Focused on readability and extensibility for PMs and quants

**Tech:** Python, NumPy, Pandas, matplotlib

---

### Micro-SaaS: Execution & Strategy Lab (WIP)

An online lab for:

- Uploading trade signals and historical data
- Simulating realistic fills using LOB microstructure
- Analyzing slippage, impact, and execution quality
- Comparing execution strategies (TWAP, VWAP, POV, custom)

This is an ongoing side project aimed at providing serious tooling
for systematic traders, PMs, and advanced retail quants.
