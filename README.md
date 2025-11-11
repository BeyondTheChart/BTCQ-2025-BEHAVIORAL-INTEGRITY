# Beyond the Chart – Quantitative & Structural Integrity Report  
**BTCQ Research Series 2025 | Institutional Quantitative Framework**  
*Authored by: Beyond the Chart Research Division*

---

## 1. Executive Summary

This document provides a complete quantitative and structural assessment of a trading account initially classified as a high-performance system.  
All computations are derived directly from the raw trade-level dataset, reconstructed and analyzed within the **Beyond the Chart Quantitative Framework**.

The results indicate that, although the account exhibits exceptional internal consistency and stable growth, the underlying statistical structure reveals **synthetic smoothness and mechanical compression** inconsistent with authentic market execution.  
The account behavior aligns with that of an **automated trading environment (EA)** operating under controlled or simulated conditions, rather than a live brokerage setting.

---

## 2. Methodology

The analysis integrates traditional financial metrics with structural diagnostics and temporal modeling.  
Each module has been applied systematically to ensure replicability and transparency.

**Modules Applied**
- **Core KPI Metrics:** CAGR, Sharpe, Sortino, Calmar, Gain-to-Pain, Profit Factor, R/R Ratio  
- **Tail Risk & Stability Metrics:** Skewness, Kurtosis, VaR, CVaR, Ulcer Index, Omega Ratio  
- **Equity Consistency Metrics:** Rolling Expectancy, Volatility Adaptation, Drawdown Mapping  
- **Root Cause Correlation Matrix:** Sharpe vs Win Rate, Trade Size, and Drawdown  
- **Edge Decay Timeline:** Rolling Sharpe and Sortino regression-based decay  
- **Monte Carlo Simulation:** 1,000 reshuffled simulations with full equity fan chart  
- **Ruin Probability Model:** Empirical survival probability estimation  
- **Hidden Exposure Metrics:** Real vs Broker-Limited Equity comparison  

All values, plots, and regressions are reproducible from the original CSV file.

---

## 3. Quantitative Findings

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Win Rate | **93.2%** | Statistically atypical under live CFD execution |
| R/R Ratio | **0.39** | Asymmetric exposure; limited reward per trade |
| Max Drawdown | **2.1%** | Improbable consistency for a retail environment |
| CAGR | **48.3%** | Unrealistic under normal market friction |
| Sharpe Ratio | **3.27** | Artificially smooth volatility regime |
| Sortino Ratio | **5.01** | Indicates downside compression |
| Edge Decay Slope | **−0.00042** | Gradual degradation of strategy efficiency |
| Operational Resilience | **88.4 / 100** | Mechanically stable execution |
| Self-Destruction Index | **1.00** | Absence of real market friction |

The account displays near-perfect linearity, low variance, and static drawdowns across all phases, suggesting algorithmic control over exposure.

---

## 4. Structural Integrity Assessment

A comparison between **reconstructed real equity** and a **broker-limited proxy** shows negligible divergence.  
This pattern implies that drawdown and volatility have been systematically constrained, producing an artificial stability envelope.

Such behavior is inconsistent with genuine CFD execution, where spread, slippage, and order latency introduce natural variance.  
The account instead follows the profile of a controlled EA environment, possibly used for demonstration or promotional purposes.

---

## 5. Root Cause Analysis

The **Root Cause Correlation Matrix** establishes the structural dependencies driving performance metrics:

| **Correlation Pair** | **ρ** | **Interpretation** |
|----------------------|-------|--------------------|
| Sharpe ↔ Win Rate | +0.71 | Mechanically optimized consistency |
| Sharpe ↔ Drawdown | −0.64 | Volatility suppression during expansion |
| Sharpe ↔ Trade Size | −0.52 | Reactive sizing logic; non-adaptive exposure |

These correlations are typical of automated averaging or grid-based systems operating in a synthetic or latency-free context.

---

## 6. Edge Decay and Behavioral Dynamics

Regression analysis of **Edge Strength** demonstrates a slow but measurable decline over time.  
The slope of **−0.00042** confirms a gradual reduction in efficiency as volatility expands.  
While operational mechanics remain consistent, profitability decays as the environment deviates from equilibrium, a signature of overfitted or volatility-sensitive automation.

---

## 7. Monte Carlo and Ruin Probability

A full empirical Monte Carlo simulation (1,000 randomized trade sequences) was performed.  

**Key Outputs**
- **Expected Final Equity:** €29,480  
- **5–95% Interval:** €25,260 – €33,980  
- **Simulated Probability of Ruin (−70% equity):** < 1%  

The simulations show exceptionally narrow dispersion, indicating low entropy and low sensitivity to trade order.  
This behavior is typical of **data homogenization**, not of live systems reacting to market uncertainty.

---

## 8. Statistical Fingerprints

Several independent indicators support the conclusion of artificial smoothness:

- **Low Drawdown Dispersion:** Stable equity across 800+ trades  
- **High Positive Autocorrelation:** Confirmed by ACF/PACF and Hurst exponent > 0.6  
- **Suppressed Tail Risk:** Minimal downside volatility relative to reward structure  
- **Rolling Metrics Stability:** Sharpe, Sortino, and Win Rate remain abnormally constant  
- **Uniform Monte Carlo Outcomes:** Lack of stochastic variance in reshuffled paths  

All these features are incompatible with genuine trade-level variability.

---

## 9. Interpretation

The quantitative and structural evidence demonstrates that:
- The account operates with exceptional internal coherence and consistency.  
- Structural volatility and behavioral randomness are absent.  
- The statistical properties correspond to an **EA executing in a synthetic or latency-free environment**.  

The dataset therefore represents a **mechanically consistent but environmentally artificial performance** — unsuitable for evaluation as a live trading record.

---

## 10. Final Assessment

| **Dimension** | **Status** | **Conclusion** |
|----------------|------------|----------------|
| Statistical Consistency | ✅ | Strong internal coherence |
| Structural Realism | ⚠️ | Artificial compression detected |
| Execution Dynamics | ⚠️ | No market-level friction present |
| Long-Term Sustainability | ⚠️ | Edge decay confirmed |
| Market Validity | ❌ | Not representative of live conditions |

**Overall Verdict:**  
The account demonstrates high mechanical precision but lacks the stochastic characteristics of real execution.  
The dataset should not be interpreted as live or broker-validated performance.

---

## 11. Licensing and Attribution

All figures and analyses are derived from the Beyond the Chart Quantitative Framework.  
Reproduction and distribution are permitted under the **Creative Commons Attribution–NonCommercial 4.0 (CC BY-NC 4.0)** license.  

© 2025 Beyond the Chart Research Division – All Rights Reserved.  
