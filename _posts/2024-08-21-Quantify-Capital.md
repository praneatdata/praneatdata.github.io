---
title: "Algorithmic Trading | Self Project"
date: 2024-08-21 00:00:00 +0530
categories: [Project]
tags: [Algorithmic Trading, self project]
---

## Overview
This project focuses on developing and implementing an **intraday Algorithmic Trading** strategy designed for the Indian stock market. The strategy was thoroughly backtested using historical data and automated for real-time trading execution.

## Project Objective
The primary goal of this project is to:
- **Develop** an intraday Algorithmic Trading strategy.
- **Implement** an automated trading system that can execute trades based on the strategy.

## Key Features
- **Data Analysis**:
  - Analyzed comprehensive **2-year OHLC** (Open, High, Low, Close) data of stocks in the **NIFTY200** index.
  - Strategically identified potential stocks for **buy/short** positions.

- **Strategy Development & Backtesting**:
  - **Developed** and **backtested** the trading strategy on **1-year** historical data.
  - Utilized the `yfinance` library for data retrieval and performed optimization of **stop-loss** and **take profit** levels.

- **Automation**:
  - **Successfully automated** trade execution using **Zerodha’s Kite Connect API**.
  - Enabled seamless transactions with real-time integration, ensuring quick and efficient order placements.

## Result
The project resulted in the creation of a **risk-optimized** intraday trading strategy that utilizes **AMO** (After Market Orders) and **Market orders**. The strategy was tested and demonstrated the capability to deliver positive returns.

## Technology Stack
- **Python**: Core language used for development and data analysis.
- **yfinance**: Library used for fetching historical stock data.
- **Zerodha Kite Connect API**: Used for automating trade execution.

[Link to the github repo](https://github.com/praneatdata/quantify-captital)
