# Self-Reflective Multi-Agent AI Architecture for Risk-Aware Algorithmic Trading

A research project investigating how lightweight multi-agent AI systems can improve algorithmic trading through risk-aware reasoning, explainability, and structured self-reflection.

## Overview

This repository contains the implementation of a proof-of-concept multi-agent AI trading architecture developed as part of a research study on explainable and risk-aware algorithmic trading.

The project compares a traditional Simple Moving Average (SMA) crossover strategy with a collaborative multi-agent system consisting of specialized agents responsible for:

- Market analysis
- Risk management
- Trade execution
- Self-reflection and decision critique

The objective is to investigate whether collaborative AI reasoning can improve trading performance while increasing transparency and auditability.

## Research Objectives

The project aims to:

- Build a benchmark SMA crossover trading strategy
- Develop a lightweight multi-agent AI trading architecture
- Evaluate the impact of risk-aware reasoning
- Investigate the effect of macroeconomic indicators
- Incorporate financial news sentiment
- Produce explainable decision logs
- Compare performance against the baseline strategy

## Research Questions

RQ1.
Can a risk-aware multi-agent AI system outperform a traditional SMA crossover strategy?

RQ2.
Does incorporating macroeconomic indicators reduce portfolio risk?

RQ3.
Does financial news sentiment improve trading decisions?

RQ4.
Do reflection logs improve explainability and post-trade diagnosis?

## System Architecture

```text
Historical Data
       │
       ▼
Market Analysis Agent
       │
       ▼
Risk Management Agent
       │
       ▼
Execution Agent
       │
       ▼
Reflection Agent
       │
       ▼
Decision Logs
```

## Repository Structure

```text
.
├── data/
├── docs/
├── notebooks/
├── src/
├── experiments/
├── outputs/
├── tests/
└── README.md
```

## Project Flow

Data Collection
      ↓
Feature Engineering
      ↓
Baseline SMA Strategy
      ↓
Multi-Agent Trading
      ↓
Risk Evaluation
      ↓
Reflection Logging
      ↓
Performance Analysis

## Data Sources

| Dataset                  | Source        | Purpose            |
| ------------------------ | ------------- | ------------------ |
| Historical Prices        | Alpha Vantage | Backtesting        |
| Technical Indicators     | Alpha Vantage | Trading signals    |
| News Sentiment           | Alpha Vantage | Sentiment analysis |
| VIX                      | FRED          | Risk filtering     |
| Macroeconomic Indicators | FRED          | Risk management    |


## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Backtesting.py (or Backtrader)
- LangGraph / AutoGen / CrewAI (optional)
- OpenAI API or local LLM
- FinBERT
- SHAP
- Matplotlib
- Plotly

