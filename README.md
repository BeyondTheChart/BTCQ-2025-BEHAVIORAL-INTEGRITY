# **Beyond the Chart – Quantitative & Structural Integrity Report**  
**BTCQ Research Series 2025 | Institutional Quantitative Framework**  
*Authored by Beyond the Chart Research Division*

---

## **1. Executive Summary**

This document presents a complete quantitative and structural integrity assessment of a trading account initially classified as a high-performance system.  
The analysis was conducted through the **Beyond the Chart Quantitative Framework**, designed to evaluate both the mathematical consistency and the environmental authenticity of trading performance.

Although the system exhibits exceptional linearity and consistency, the statistical structure reveals **synthetic compression and mechanical smoothness**, characteristic of an **algorithmic execution (EA)** under controlled or non-live conditions.  
This report combines quantitative, structural, and probabilistic diagnostics to determine whether the account’s performance represents genuine market behavior or a simulated environment.

---

## **2. Core KPI Metrics**

Key performance indicators establish the foundation for the analysis of stability and proportionality between return and risk.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Win Rate | **93.2%** | Statistically excessive for live CFD markets |
| R/R Ratio | **0.39** | Limited reward per unit of risk |
| Max Drawdown | **2.1%** | Unrealistically low given market conditions |
| CAGR | **48.3%** | Compounded return inconsistent with frictional markets |
| Sharpe Ratio | **3.27** | Artificially stable volatility regime |
| Sortino Ratio | **5.01** | Downside volatility suppression |
| Calmar Ratio | **22.9** | Outlier-level reward-to-risk |
| Gain-to-Pain | **3.74** | Suggests systematic bias in profit aggregation |

**Visual Metrics**

![Rolling Sharpe Ratio](images/rolling_sharpe_ratio.png)  
*Rolling Sharpe ratio (100 trades) demonstrating smooth and uniform performance.*

![Rolling Sortino Ratio](images/rolling_sortino_ratio.png)  
*Rolling Sortino ratio with minimal downside volatility fluctuation.*

![Drawdown Curve](images/drawdown_curve.png)  
*Equity and drawdown relationship indicating controlled exposure.*

---

## **3. Tail Risk & Stability Metrics**

The tail-risk module quantifies asymmetry and extreme-event behavior.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Skewness | **0.48** | Mild positive bias in returns distribution |
| Kurtosis | **2.11** | Suppressed tails, consistent with synthetic data |
| VaR (95%) | **−0.18%** | Minimal downside dispersion |
| CVaR (95%) | **−0.26%** | Low conditional loss concentration |
| Stability Ratio | **0.83** | Indicates statistically compressed variance |

**Visual Metrics**

![PnL Distribution](images/pnl_distribution.png)  
*Trade-level profit distribution showing controlled tail risk.*

![QQ Plot](images/qq_plot.png)  
*QQ plot confirming non-Gaussian, smoothed distribution profile.*

![Rolling Expectancy](images/rolling_expectancy.png)  
*Expectancy and standard deviation highlighting variance compression.*

---

## **4. Structural Integrity Assessment**

The reconstructed equity curve demonstrates negligible deviation between real equity and a broker-limited proxy, implying absence of real-market friction.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Max Real DD | **2.1%** | Unrealistically consistent |
| Max Broker DD | **2.0%** | Indicates identical exposure behavior |
| Self-Destruction Index | **1.00** | No deviation between structural layers |
| Edge Health | **94.6%** | Stable internal mechanics, artificial resilience |

**Visual Metrics**

![Equity Comparison](images/equity_comparison.png)  
*Real vs broker-limited equity: no structural separation observed.*

![Drawdown Comparison](images/drawdown_comparison.png)  
*Parallel drawdown traces confirm static risk profile.*

---

## **5. Root Cause Correlation Matrix**

The correlation matrix isolates the causal dependencies between key behavioral and structural variables.  

| **Correlation Pair** | **ρ** | **Interpretation** |
|----------------------|-------|--------------------|
| Sharpe ↔ Win Rate | **+0.71** | Mechanically optimized consistency |
| Sharpe ↔ Drawdown | **−0.64** | Negative link to volatility stress |
| Sharpe ↔ Trade Size | **−0.52** | Reactive exposure scaling |

**Visual Metrics**

![Root Cause Correlation Matrix](images/root_cause_matrix.png)  
*Correlation heatmap illustrating structural dominance over behavioral dynamics.*

---

## **6. Edge Decay Timeline**

The Edge Decay module captures performance deterioration across time, revealing the sustainability of trading efficiency.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Slope | **−0.00042** | Progressive edge degradation |
| Correlation (r)** | **−0.68** | Strong negative trend over trade index |
| Decay Classification | **Moderate Structural Decay** | Declining performance under volatility expansion |

**Visual Metrics**

![Edge Decay Timeline](images/edge_decay_timeline.png)  
*Edge decay trend illustrating steady loss of efficiency.*

![Edge Forecast](images/edge_forecast.png)  
*ARIMA-based forecast showing anticipated collapse zone.*

---

## **7. Monte Carlo Simulation & Risk of Ruin**

Monte Carlo simulations (1,000 reshuffled sequences) were performed to test path dependence and probabilistic ruin risk.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Expected Final Equity | **€29,480** | Mean equity after randomized sequencing |
| Std of Final Equity | **€1,840** | Minimal dispersion—synthetic uniformity |
| 5–95% Interval | **[€25,260 – €33,980]** | Narrow confidence band |
| Risk of Ruin (30% balance)** | **<1%** | Unrealistically low probability |

**Visual Metrics**

![Monte Carlo Distribution](images/montecarlo_distribution.png)  
*Final equity distribution under 1,000 randomized simulations.*

![Monte Carlo Fan Chart](images/montecarlo_fan_chart.png)  
*Reshuffled equity paths confirming deterministic system behavior.*

![Survival Probability](images/survival_curve.png)  
*Simulated survival probability curve showing near-zero ruin likelihood.*

---

## **8. Hidden Exposure & Destruction Index**

The Beyond Risk Metrics module quantifies the divergence between operational drawdown and structural constraints.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Max DD (Real) | **€530 (2.1%)** | True drawdown under unconstrained equity |
| Max DD (Broker-Limited)** | **€505 (2.0%)** | Broker-side limited version |
| Self-Destruction Index | **1.00** | Identical drawdown scaling |
| Operational Resilience Score | **88.4 / 100** | Stable, mechanical consistency |

**Visual Metrics**

![Hidden Exposure Table](images/hidden_exposure_table.png)  
*Full comparative table of structural and operational metrics.*

![Beyond Risk Comparison](images/beyond_risk_comparison.png)  
*Drawdown comparison and stability correlation.*

---

## **9. Statistical Fingerprints**

Additional diagnostics confirm data manipulation or simulation traits:

- Uniform volatility profile across >800 trades  
- No stochastic variance under reshuffle  
- Fixed-size position clusters without spread variation  
- High serial correlation (Hurst > 0.6)  
- Non-random streak structure  

**Visual Metrics**

![Streak Distribution](images/streak_distribution.png)  
*Sequential win/loss streaks showing mechanical clustering.*

![ACF PACF](images/acf_pacf.png)  
*Autocorrelation and partial autocorrelation confirming serial dependency.*

---

## **10. Final Assessment**

| **Dimension** | **Status** | **Conclusion** |
|----------------|------------|----------------|
| Statistical Consistency | ✅ | Exceptional internal coherence |
| Structural Realism | ⚠️ | Artificial compression detected |
| Execution Dynamics | ⚠️ | No market-level friction present |
| Edge Sustainability | ⚠️ | Decay trend confirmed |
| Market Authenticity | ❌ | Incompatible with live market behavior |

**Summary Verdict:**  
The analyzed system is **mechanically stable but structurally artificial**.  
Performance characteristics indicate **synthetic or demo-environment data**, optimized for visual stability rather than real-world execution.

---

## **11. License and Attribution**

This repository and all included visual assets are released under the  
**Creative Commons Attribution–NonCommercial 4.0 (CC BY-NC 4.0)** license.  

> © 2025 Beyond the Chart Research Division  
> Quantitative & Behavioral Analysis Framework  
> All rights reserved.
