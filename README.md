![Paris Airbnb Project Cover](paris.png)
# 🏙️ Paris Airbnb Supply & Pricing Shift After 2015

## Executive Summary

Paris faced a key short-term rental question around 2015:

> **Did Airbnb regulation change market supply and pricing?**

This analysis found a clear market signal: **new host/listing growth peaked in 2015 with 12,147 new entries, then dropped sharply. At the same time, average prices increased from €103.65 in 2015 to €143.52 in 2020.**

This suggests a tighter market after 2015: slower supply growth, less competition, and higher average prices.

---

## Business Context

**Stakeholder:** City policy team / short-term rental strategy team  
**Business goal:** Understand whether the Paris Airbnb market showed signs of supply slowdown and price pressure around the 2015 regulation period.

Short-term rental regulation can create a trade-off:

- 🏠 Protect local housing
- 📉 Slow new Airbnb supply
- 💰 Increase traveler prices if competition drops

---

## Key Metrics

| Metric | Value |
|---|---:|
| Clean Paris listings analyzed | **64,628** |
| Average nightly price | **€113.20** |
| Median nightly price | **€80.00** |
| Peak new host/listing year | **2015** |
| New hosts/listings in 2015 | **12,147** |
| Avg. price change, 2015 → 2020 | **+38.5%** |

---

## Key Business Questions

1. Which Paris areas are premium vs affordable?
2. Did new Airbnb supply slow after 2015?
3. Did prices rise after supply growth slowed?
4. What should stakeholders monitor next?

---

## Key Insights

### 1. 🗺️ Location is the strongest pricing signal

| Area | Average price |
|---|---:|
| Elysee | **€211.37** |
| Menilmontant | **€74.96** |

**Insight:** Elysee is almost **2.8x more expensive** than Menilmontant.  
**Recommendation:** Pricing and policy decisions should be made at neighbourhood level, not using one Paris-wide average.

---

### 2. 📉 New Airbnb supply growth slowed sharply after 2015

| Year | New hosts/listings | Change vs 2015 peak |
|---:|---:|---:|
| 2015 | **12,147** | Peak |
| 2016 | **8,867** | **-27.0%** |
| 2017 | **4,585** | **-62.3%** |
| 2018 | **4,294** | **-64.6%** |
| 2019 | **5,685** | **-53.2%** |

**Insight:** 2015 was the market growth peak. After that, new host/listing growth dropped strongly.  
**Recommendation:** Policy teams should track **new listing growth**, not only total listing volume.

---

### 3. 💰 Prices rose after supply growth slowed

Average price fell before 2015:

- **2009:** €159.64  
- **2014:** €100.25  
- Change: **-37.2%**

Average price rose after 2015:

- **2015:** €103.65  
- **2020:** €143.52  
- Change: **+38.5%**

**Insight:** Prices started rising again after new supply growth slowed.  
**Recommendation:** Supply and price should be monitored together. A supply slowdown can create price pressure.

---

## Business Impact

This analysis helps stakeholders:

- Identify premium and affordable Airbnb zones
- Understand supply slowdown after 2015
- Track whether slower new listing growth is linked to higher prices
- Build better neighbourhood-level pricing or regulation strategies

---

## Limitations

This is a descriptive analysis. It shows market patterns, but it does **not** prove regulation caused the changes.

Other factors may also affect prices:

- Tourism demand
- Seasonality
- COVID-19
- Economic conditions
- Market saturation

Also, yearly trends are based on `host_since`, not historical booking prices.

---

## Technical Appendix

**Tools:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

**Main steps:**

1. Cleaned Airbnb Paris listing data
2. Compared prices by neighbourhood and capacity
3. Analyzed yearly new host/listing growth
4. Checked price movement around 2015
5. Added COVID sensitivity check

---

## Final Takeaway

> **Paris Airbnb supply growth peaked in 2015 and slowed sharply afterward. Average prices then increased from 2015 to 2020, suggesting a tighter market with fewer new entrants and higher price pressure.**
