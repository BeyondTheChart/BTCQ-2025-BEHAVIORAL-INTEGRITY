# **Beyond the Chart – Quantitative & Structural Integrity Report**

### **BTCQ Research Series 2025 | Institutional Quantitative Framework**

*Authored by Beyond the Chart Research Division*

---

## **1. Executive Overview**

A full-spectrum structural and quantitative audit conducted under the **BTCQ Institutional Framework** to evaluate algorithmic integrity, statistical robustness, and environmental authenticity.

This repository provides a **comprehensive quantitative, structural, and behavioral assessment** of a high-frequency algorithmic trading system analyzed using the **Beyond the Chart Quantitative & Behavioral Framework (BTCQ Suite v2.5)**.

The analysis integrates **over 30 advanced quantitative metrics** covering performance, stability, structural integrity, and risk forecasting.

While the strategy exhibits remarkable consistency, the resulting data patterns reveal **structural compression** and **synthetic volatility smoothing** — both inconsistent with genuine market execution.

All observations are supported by **statistical evidence derived from trade-level data**, ensuring full methodological transparency.

---

## **2. Core Performance Metrics**

This section evaluates the system’s long-term performance stability and risk-adjusted efficiency.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| CAGR | **48.3%** | Unrealistically high growth for real CFD execution |
| Sharpe Ratio | **3.27** | Exceptional stability — characteristic of over-optimized EAs |
| Sortino Ratio | **5.01** | Indicates artificial downside suppression |
| Calmar Ratio | **23.0** | Inconsistent with natural drawdown distribution |
| Gain-to-Pain | **3.88** | Suggests filtered or synthetic return series |

**Figures:**  
![Rolling Sharpe Ratio](images/rolling_sharpe_ratio.png)  
![Rolling Sortino Ratio](images/rolling_sortino_ratio.png)  
![CAGR & Calmar Ratio](images/cagr_calmar_ratio.png)  
![Gain to Pain Distribution](images/gain_to_pain.png)

---

## **3. Tail Risk & Distribution Stability**

Tail risk metrics expose **non-normality** and **artificial compression** of trade-level volatility.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Skewness | **+0.88** | Mild positive bias, consistent with grid or averaging logic |
| Kurtosis | **1.94** | Indicates smoothed distribution tails |
| VaR (95%) | **−€37.22** | Minimal tail losses, unrealistic in high-frequency trading |
| CVaR (95%) | **−€55.81** | Confirms volatility underestimation |

**Figures:**  
![Trade Distribution](images/trade_distribution.png)  
![QQ Plot – Trade Returns](images/qq_plot_returns.png)  
![Rolling Expectancy](images/rolling_expectancy.png)  
![Rolling Volatility](images/rolling_volatility.png)

---

## **4. Equity Consistency & Drawdown Dynamics**

Equity progression reveals an exceptionally linear equity curve with minimal drawdown variance — a typical signature of synthetic or backtested environments.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Max Drawdown | **2.1%** | Statistically improbable in real execution |
| Edge Health | **94.6%** | Near-perfect curve stability |
| Consistency Index | **0.91** | Indicates mechanical uniformity |
| Behavioral Decay Correlation | **−0.65** | Suggests degradation under volatility stress |

**Figures:**  
![Equity Curve](images/equity_curve.png)  
![Drawdown Map](images/drawdown_map.png)  
![Behavioral Decay](images/behavioral_decay.png)  
![KDE Distribution](images/kde_distribution.png)

---

## **5. Root Cause & Structural Correlation Matrix**

This matrix quantifies how key performance metrics interact, revealing whether degradation originates from **structural instability** or **behavioral components**.

| **Correlation Pair** | **ρ** | **Interpretation** |
|----------------------|-------|--------------------|
| Sharpe ↔ Win Rate | **+0.71** | Structural dependence — consistent execution pattern |
| Sharpe ↔ Drawdown | **−0.64** | Efficiency loss under stress |
| Sharpe ↔ Trade Size | **−0.52** | Suggests reactive size increase during drawdowns |

**Figure:**  
![Root Cause Matrix](images/root_cause_matrix.png)

---

## **6. Edge Decay & Temporal Regression**

The *Edge Decay Timeline* measures how the algorithm’s efficiency erodes over time, revealing the onset of structural fatigue.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Edge Decay Slope | **−0.00042** | Gradual deterioration of profitability |
| Correlation (r) | **−0.68** | Negative link between edge and volatility |
| Decay Regime | **Progressive** | Edge weakens during volatile market conditions |

**Figures:**  
![Edge Strength Curve](images/edge_strength_curve.png)  
![Edge Decay Trendline](images/edge_decay_timeline.png)

---

## **7. Monte Carlo Simulation & Scenario Forecast**

Monte Carlo reshuffle simulations assess the algorithm’s robustness under randomized trade sequencing and stress conditions.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Expected Final Equity | **€29,480** | Mean outcome over 1,000 simulations |
| 5–95% Interval | **[€25,260 – €33,980]** | Narrow band suggests homogenized returns |
| Simulated Probability of Ruin | **<1%** | Unrealistically low — artificial data variance |

**Figures:**  
![Monte Carlo Fan Chart](images/monte_carlo_fan_chart.png)  
![Final Equity Distribution](images/final_equity_distribution.png)  
![Survival Probability Curve](images/survival_probability_curve.png)

---

## **8. Risk of Ruin & Survival Probability**

This model combines theoretical and empirical ruin probability analysis to assess systemic fragility under stress.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Theoretical Risk of Ruin | **0.0%** | Mathematically impossible in real markets |
| Simulated Ruin Probability | **1.2%** | Indicates filtered loss distribution |
| Cumulative Survival Probability | **>98%** | Consistent with demo or non-frictional environment |

**Figures:**  
![Risk of Ruin](images/risk_of_ruin.png)  
![Cumulative Risk Curve](images/cumulative_risk_curve.png)

---

## **9. Hidden Exposure & Self-Destruction Index**

The *Beyond Risk Metrics* module compares **real-equity drawdown** against a **broker-limited simulation**, replicating CFD leverage and margin thresholds.

| **Metric** | **Value** | **Interpretation** |
|-------------|------------|--------------------|
| Real Max Drawdown | **2.1%** | Unrealistically compressed |
| Broker-Limited Max Drawdown | **2.1%** | Identical — synthetic feed |
| Self-Destruction Index | **1.00** | No market friction detected |

**Figures:**  
![Equity Comparison – Real vs Broker](images/equity_real_vs_broker_limited.png)  
![Drawdown Comparison](images/drawdown_comparison_real_vs_broker_simulation.png)  
![Hidden Exposure Summary](images/hidden_exposure_table.png)  
![Self-Destruction Index](images/self_destruction_index.png)

---

## **10. Edge Collapse Diagnostic**

The *Edge Collapse Root Cause Analysis* isolates the leading factors driving efficiency loss and operational breakdown.

| **Dominant Cause** | **Correlation** | **Interpretation** |
|--------------------|-----------------|--------------------|
| Structural Correlation | **−0.64** | Edge collapse triggered by market volatility |
| Behavioral Correlation | **+0.31** | Minor impact — EA suppresses trader bias |
| Size-Exposure Interaction | **−0.52** | Aggressive scaling in stress phases |

**Figure:**  
![Edge Collapse Matrix](images/edge_collapse_root_cause_matrix.png)

---

## **11. Behavioral Consistency & Position Bias Analysis**

Although this system is fully algorithmic, the behavioral layer analysis identifies deterministic biases and size-related distortions.

Results confirm the **absence of human-driven bias**, but highlight **systematic scaling behavior**, consistent with grid-style logic.

**Figures:**  
![Size Bias Analysis](images/position_sizing_bias_ratio.png)  
![Win-Loss Streaks](images/streaks_consecutive_wins_losses.png)

---

## **12. Consolidated Executive Summary**

The combined findings across all modules indicate that:

- The strategy operates under **synthetic, non-frictional market conditions**.  
- **Volatility compression** and **drawdown uniformity** confirm demo-like data.  
- Performance results, though internally coherent, are **environmentally invalid**.  
- Edge decay trends show rapid profitability loss once volatility expands.  
- The system most likely functions as a **marketing demonstration algorithm**, not a live trading model.

> **Final Verdict:**  
> The analyzed trading system displays **logical quantitative consistency** but **environmental artificiality**.  
> Its results cannot be considered representative of live market performance.

---

## **13. Framework Attribution & Licensing**

All computations and visualizations were generated using the  
**Beyond the Chart Quantitative & Behavioral Framework (BTCQ Suite v2.5)**.

This framework integrates:
- Quantitative metrics (Sharpe, Sortino, Calmar, Gain-to-Pain)  
- Structural diagnostics (Edge Decay, Root Cause Matrix, Monte Carlo Resampling)  
- Behavioral correlation mapping (if applicable)  
- Drawdown integrity and survival forecasting  

**License:**  
Released under the **CC BY-NC-ND 4.0 International License**.  
Redistribution or modification is prohibited without explicit authorization.

> © **Beyond the Chart Research Division**  
> Quantitative & Behavioral Framework  
> All rights reserved — for institutional and research purposes only.
