# Collateralized Debt Obligation (CDO) Structuring and Tranche Analysis 

## Overview
This project demonstrates a simulation-based analysis of a Collateralized Debt Obligation (CDO) structure. The focus is on modeling cash flows, structuring tranches, and evaluating credit risk to meet credit rating standards. The analysis provides insights into tranche performance and overall portfolio risk.

## Key Features
- **Portfolio Composition**: The portfolio comprises 10 speculative-grade corporate bonds, each with a face value of $10 MM, a 6% annual coupon, a 4% annual default probability, and a 60% loss given default (LGD).  
- **Cash Flow Simulation**: Quarterly cash flows are modeled to account for defaults, LGD, and the correlation (0.20) between bond defaults.  
- **Tranche Structuring**: Cash flows are distributed via a waterfall mechanism prioritizing payments to Class A, followed by Class B, with residuals retained as equity.  
- **Risk and Valuation Metrics**: Calculations include Return on Equity (ROE), loss probabilities, and expected loss given default.  

---

## Methodology

1. **Simulation Model**: 
   - Simulated aggregate quarterly cash flows for a 5-year horizon.
   - Incorporated default probabilities and correlations between bond defaults.
   
2. **Waterfall Rules**:
   - Prioritized cash flows to tranches based on seniority.
   - Ensured Class A ($20 MM) tranche met Moody’s Aa credit rating standards.

3. **Risk and Valuation Analysis**:
   - Evaluated Return on Equity (ROE) for equity holders.
   - Calculated loss probabilities and LGD for Class A and Class B tranches.

---

## Findings

1. **Portfolio Insights**:
   - Total face value of the bond portfolio: $100 MM.
   - Annual default probability: 4%.
   - LGD: 60%.

2. **Tranche Analysis**:
   - **Class A**:
     - Notional Value: $20 MM.
     - Coupon Rate: 2%.
     - Met Moody’s Aa rating standard.
   - **Class B**:
     - Notional Value: $10 MM.
     - Coupon Rate: 4%.

3. **Risk Metrics**:
   - Return on Equity (ROE): **19.21%**.
   - Loss given default: **0.063%**.
   - Expected loss probability: **0.00005219**.
