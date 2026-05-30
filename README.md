# E-Commerce Funnel Analysis & A/B Test Design

End-to-end funnel analysis and experiment design on 80,000 
e-commerce sessions — identifying checkout drop-off, quantifying 
revenue impact, and designing a statistically rigorous A/B test.

---

## Key findings

- Overall session-to-purchase conversion: **10.81%**
- Biggest funnel drop: **72% of checkout-intent users did not purchase**
- Mobile checkout-to-purchase rate: **22.99%** vs desktop **23.82%**
- Closing the mobile gap = estimated **£7,762 additional monthly revenue**

---

## Experiment design

| Parameter | Value |
|---|---|
| Hypothesis | Simplified 1-page mobile checkout increases conversion |
| Primary metric | Checkout-to-purchase rate (mobile) |
| Baseline rate | 22.99% |
| Minimum detectable effect | 1pp |
| Confidence level | 95% |
| Statistical power | 80% |
| Required sessions per variant | 28,213 |
| Estimated test duration | 43 days |

---

## Notebook structure

1. Funnel construction using proxy logic on session-level data
2. Device segmentation — mobile vs desktop vs tablet
3. Channel analysis — organic, paid, social, email, referral
4. Revenue impact quantification
5. Visualisation — funnel chart and device comparison
6. Full A/B test brief with sample size calculation
7. Executive summary memo

---

## Tools

Python · Pandas · Matplotlib · SciPy

---

## Dataset

80,000 session-level e-commerce records with device type, 
acquisition channel, cart additions, and conversion outcome.
