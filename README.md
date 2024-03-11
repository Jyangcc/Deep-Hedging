# Deep-Hedging

This project implements and compares the effectiveness of delta hedging and deep hedging (utilizing neural networks) when selling a European option. The comparison is based on delta hedging of Black-Scholes model and Heston model.

## Setting:
- Considers a discrete-time financial market with a finite time horizon T and trading dates.
- Involves market information available at each time point, stocks' mid-prices as stochastic processes, and contingent claims.
## Trading Strategies:
- Engages in trading assets through strategies represented by allocations within assets at different time points.
- Calculates trading gains or losses under a strategy based on asset price changes.
## Measuring Risk:
- Aims to reduce risk associated with derivative portfolios using risk measures like Convex Risk Measures.
- Defines Convex Risk Measures as monotone decreasing, convex, and cash-invariant functions.
- This project use CVaR as risk measure.
## Optimal Hedging Strategy:
- Defines an optimal hedging strategy that minimizes risk within specific constraints based on a given convex risk measure.

## Reference: 

[Deep_Hedging](<https://arxiv.org/abs/1802.03042>)

