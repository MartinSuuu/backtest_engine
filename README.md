# backtest_engine

A lightweight, vectorized backtesting engine for systematic strategies:
- T+1 execution (no look-ahead)
- Portfolio weights & leverage constraints
- Transaction costs based on turnover
- Performance metrics (Sharpe, CAGR, Max Drawdown)
  
## Quick Start

```bash
# 1) create venv (optional but recommended)
python -m venv .venv
source .venv/bin/activate

# 2) install
pip install -r requirements.txt

# 3) run demo
python scripts/run_momentum.py
