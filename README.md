![Paris Airbnb Project Cover](paris.png)

# 🏙️ Paris Airbnb Pricing & Regulation Impact (2015)
### From “data analysis” to “decision-ready story” (2026 BI style)

> **One-line story:** **After 2015 regulations, new host growth fell sharply and average prices started rising again — likely due to reduced competition.**

---

## 🎯 Why this project exists (Business goal)
Airbnb’s growth in Paris triggered housing pressure and community concerns. In **2015**, regulations limited short-term rentals.
This project answers one business question:

✅ **Did the 2015 regulation reduce supply growth — and did that change prices?**

This is not a “notebook walkthrough”.  
This is a **decision-ready story**: **So what happened? Why does it matter? What should we do next?**

---

## 🧠 Key Questions
1) Which neighbourhoods are **cheapest vs most expensive**?  
2) In the **most expensive neighbourhood**, how does price change with **accommodates**?  
3) Over time: what happened to **new hosts** and **average price**?  
4) What does the **2015 policy point** change in the market dynamics?

---

## 📌 What I used (Tools) + Why
- **Python**: fast, reproducible analysis  
- **pandas**: filtering, grouping, resampling time series  
- **numpy**: basic numeric support  
- **matplotlib + seaborn**: clean, executive-friendly charts (high data-to-ink ratio)

**Key technical choices (simple, but important):**
- `parse_dates=["host_since"]` → correct time series analysis  
- `encoding="ISO-8859-1"` → avoid CSV Unicode errors  
- `resample("YE")` → pandas 2026-compatible yearly aggregation  
- Added `listing_count` in group tables → prevents wrong conclusions from thin data

---

## 🗂️ Dataset
- Source: **Maven Analytics — Airbnb Listings dataset**
- Scope: **Paris listings**
- Core fields used:
  - `host_since` (date)
  - `neighbourhood`
  - `accommodates`
  - `price`

---

## ✅ What we built (Deliverables)
### 1) **Price by neighbourhood** (where price differences really come from)
A clean table that supports a clear bar chart:
- neighbourhood → average price (sorted low → high)

### 2) **Price by accommodates (premium area)**  
We focus on the most expensive neighbourhood and answer:
- accommodates → average price  
- plus `listing_count` to detect thin data

### 3) **Over time (yearly)**  
A time series table:
- `new_hosts` (count per year)
- `avg_price` (mean price per year)

### 4) Charts (Objective 3)
- Bar chart: neighbourhood vs avg_price  
- Bar chart: accommodates vs avg_price (premium area)  
- Line chart: new_hosts over time  
- Line chart: avg_price over time  
- **Bonus**: dual-axis chart (hosts + price in one view)

---

# 🔥 Findings (Headlines, not titles)

## 💸 1) “Neighbourhood is the main price driver in Paris”
Prices are not evenly distributed across the city.
Some areas have a strong premium (tourist + luxury zones).

**So what?**  
City-level averages can hide the real story. Pricing and policy impact must be read **by neighbourhood**.

**Now what?**  
Segment strategy by neighbourhood. For decisions, avoid using one global average.

---

## 🛏️ 2) “Bigger capacity usually costs more — but extreme groups can be thin data”
In the premium area, higher `accommodates` tends to show higher average prices.
But very large accommodates values can have **very few listings**, which creates unstable averages.

**So what?**  
Averages can mislead when data is thin.

**Now what?**  
Use `listing_count` rules (example: show groups with at least 10 listings) or use robust metrics (median/percentiles).

---

## 🧑‍🏠 3) “After 2015, new host growth drops sharply”
The number of new hosts rises strongly up to 2014–2015, then falls after the regulation period.

**So what?**  
The regulation appears to achieve its core goal: **slowing supply growth**.

**Now what?**  
Measure the drop by neighbourhood (policy impact may be stronger in hotspots).

---

## 💰 4) “When competition decreases, prices rise again”
As new host growth slows, average prices trend upward again.

**So what?**  
This supports a strong market mechanism:
**Supply growth ↓ → competition ↓ → price ↑**

**Now what?**  
Do deeper causal checks (see “Next steps”) before making policy-level claims.

---

# ✅ Bottom-line story (So what + Now what)
### 🚩 So what happened?
**2015 regulation period aligns with fewer new hosts and rising prices.**

### 🧭 What should we do next?
This project is a strong directional signal. Next steps should strengthen causality and decision confidence.

---

## 🧭 Recommended Next Steps (Actionable)
1) **Pre vs Post 2015 comparison**
   - before/after split, effect size, confidence checks

2) **Neighbourhood segmentation**
   - hotspot areas vs residential areas  
   - is the regulation effect stronger in premium zones?

3) **Triangulation**
   - validate with additional metrics (availability, review volume, occupancy proxies if available)

4) **Robust pricing metrics**
   - median price, percentiles, remove thin groups, outlier handling

---

## ⚠️ Limitations (Professional honesty)
- This analysis shows strong **correlation**, not guaranteed causation.
- External factors (tourism, macro trends, platform changes, COVID) may also affect price and supply.

Still, the **timing and direction** of the changes provide a compelling policy-impact narrative.

---

## ▶️ How to run (Reproducibility)
1) Create environment (example):
   - Python 3.x
   - pandas, numpy, matplotlib, seaborn
2) Put the dataset CSV in a `/data` folder
3) Run the notebook from top to bottom

---

## 📁 Suggested Repo Structure
