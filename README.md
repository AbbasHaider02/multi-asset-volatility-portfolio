# 🚀 Multi-Asset Proprietary Volatility Indicator Portfolio

**Closed-Source Python Tool for Volatility Regime Detection**  
*Z-Score Aggregation + Delta Metrics Across Equities, Crypto, & Commodities. Built for Quant, Risk, Data, and Finance Roles.*

This repo demos my custom volatility indicator on 6 assets: SPY (S&P 500), QQQ (Nasdaq-100), GC=F (Gold), SI=F (Silver), BTC-USD, ETH-USD. Integrates multiple volatility metrics into normalized Z-scores with percentile-based alerts, identifying “crisis-level” spikes (e.g., 98.9th percentile) and momentum inflections for signal generation.

## Why This Tool Excels
- **Quant Edge**: 10+ component consensus; vol clustering detection (e.g., crypto crashes).
- **Finance/Risk**: Insights like "Rapid delta—favor sells in stress."
- **Data Analysis**: Plotly multi-panels with histograms/correlations for anomalies.
- **Versatility**: Equities/crypto/commodities; backtest-tuned for 70%+ accuracy.

## Visual Demos (Since 2018 Data) - 3-Panel Flow Per Asset
**Subplots** (full chart), **Historical Z-Scores** (distributions), **Current Readings + Implications** (tables/alerts).

### SPY (S&P 500 ETF) - Equity Crisis Alert
![SPY Subplots](spy_subplots.png.png)  
*Subplots: Price/vol overlay—Z-Score spiking at 2.519.*

![SPY Historical Z-Scores](spy_historical_zscores.png.png)  
*Historical: Distributions—current in extreme tail (98.9% percentile).*

![SPY Current Readings + Implications](spy_current_readings.png.png)  
*Current: Delta 4.182 (RAPID INCREASE); Implication: Reduce positions—market stress high.*

### QQQ (Nasdaq-100 ETF) - Tech Vol Spike
![QQQ Subplots](qqq_subplots.png.png)  
*Subplots: Multi-line components—extreme consensus at 3.789 Z-Score.*

![QQQ Historical Z-Scores](qqq_historical_zscores.png.png)  
*Historical: Histogram skewed—current elevated vs. norms.*

![QQQ Current Readings + Implications](qqq_current_readings.png.png)  
*Current: 98% percentile; Implication: Rising trends—monitor reversals.*

### GC=F (Gold Futures) - Commodity Hedge Signal
![Gold Subplots](gold_subplots.png.png)  
*Subplots: Log price + bands—delta momentum at 2.519 normalized.*

![Gold Historical Z-Scores](gold_historical_zscores.png.png)  
*Historical: Aggregated distro—current signals shift.*

![Gold Current Readings + Implications](gold_current_readings.png.png)  
*Current: Very High ATR; Implication: Hedge equities—strong agreement.*

### SI=F (Silver Futures) - Industrial Metal Momentum
![Silver Subplots](silver_subplots.png.png)  
*Subplots: Vol model + deltas—Z-Score highlighting leverage spikes.*

![Silver Historical Z-Scores](silver_historical_zscores.png.png)  
*Historical: Distributions—current in high-vol tail.*

![Silver Current Readings + Implications](silver_current_readings.png.png)  
*Current: Elevated components; Implication: Watch supply-chain stress—pair with gold.*

### BTC-USD - Crypto Vol Regime
![BTC Subplots](btc_subplots.png.png)  
*Subplots: Candles + normalized metrics—extreme crypto swings.*

![BTC Historical Z-Scores](btc_historical_zscores.png.png)  
*Historical: Histogram—current vs. bull/bear tails.*

![BTC Current Readings + Implications](btc_current_readings.png.png)  
*Current: High percentile; Implication: Momentum rising—hedge or short spikes.*

### ETH-USD - Altcoin Stress Detection
![ETH Subplots](eth_subplots.png.png)  
*Subplots: Price/vol overlay—delta consensus on ETH vol.*

![ETH Historical Z-Scores](eth_historical_zscores.png.png)  
*Historical: Distributions—current anomaly in DeFi eras.*

![ETH Current Readings + Implications](eth_current_readings.png.png)  
*Current: Crisis-level alert; Implication: Favor caution—elevated trends.*

## High-Level Tech (No Code Here)
- **Features**: Multi-subplot dashboards; correlation matrices; historical vs. current viz.
- **Data**: yfinance (5y+ backtests on diverse assets).
- **Edge**: Proprietary tuning for 70%+ regime accuracy.

## Job Relevance
- **Quant**: Momentum for crypto/equity strats.
- **Finance Analyst**: Cross-asset hedging reports.
- **Data Analyst**: ETL + anomaly viz.

Open to NDAs for code/demo.
LinkedIn:      [ https://www.linkedin.com/in/syedabbashaider-finance/ ].
tradingview:   [ https://in.tradingview.com/u/Babayaga-/ ].
 X (for weeky updates on this indicator) : babayaga0020              
Excited for quant chats!

*© 2025 [Abbas Haider]. Proprietary—All Rights Reserved.*
