## Core Framework & Methodology

- **Data Architecture**
  Engineered an automated data pipeline utilizing `yfinance` to ingest, scrub, and filter 7 years of daily multi-asset market data, transforming raw historical prices into discrete returns to form the foundational time-series for quantitative modeling.

- **Active Framework**
  Developed a Dynamic Regime-Switching model utilizing a lagged moving-average filter and state-dependent Mean-Variance Optimization, tactically rotating into a Global Minimum Variance (GMV) portfolio to mitigate contractionary drawdowns.

  <img width="600" height="1134" alt="Screenshot 2026-03-08 190403" src="https://github.com/user-attachments/assets/13ad1758-74d5-4cf0-839d-f16bdc98c218" />




- **Passive Framework**
  Deployed Hierarchical Risk Parity (HRP) via agglomerative clustering and recursive bisection, circumventing traditional covariance inversion instability to achieve mathematically robust, out-of-sample diversification.

<img width="600" height="1043" alt="Screenshot 2026-03-08 190417" src="https://github.com/user-attachments/assets/15dbc39a-fddd-43f8-bfe3-cd242a46d632" />


  

- **Impact & Stack**
  Built an end-to-end `Python` backtesting engine (`NumPy`, `Pandas`, `SciPy`, `Matplotlib`) to evaluate both frameworks, empirically quantifying the statistical trade-offs between tactical alpha generation and systemic risk mitigation.

  <img width="600" height="806" alt="Screenshot 2026-03-08 190448" src="https://github.com/user-attachments/assets/1c5ed026-ec5d-47cc-9a57-38f157be2ec6" />
