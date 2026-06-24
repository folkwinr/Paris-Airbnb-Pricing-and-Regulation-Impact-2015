# Assumptions

This analysis is based on a few important assumptions.

## 1. `host_since` represents market entry

I used `host_since` as a signal for when hosts/listings entered the market.

This helps measure yearly supply growth.

**Note:** `host_since` shows when the host joined Airbnb, not always when each listing was created.

---

## 2. New hosts/listings represent supply growth

Listings grouped by `host_since` year are used as a simple supply growth signal.

If new hosts/listings fall after 2015, it suggests slower market entry.

**Note:** This is not a perfect unique host count. A stronger version would use `host_id`.

---

## 3. 2015 is treated as the key market point

2015 is used as the main reference year because it was the peak year for new hosts/listings.

- **2015:** 12,147 new hosts/listings

The analysis checks what happened after this peak.

---

## 4. Average price shows market direction

Average price is used to understand overall price movement.

Key price signal:

- **2015:** €103.65
- **2020:** €143.52
- Change: **+38.5%**

**Note:** Average price can be affected by expensive listings, so median price was also reviewed.

---

## 5. 2021 is treated carefully

2021 may be affected by COVID-19 and low data volume.

Because of this, the main post-2015 price trend focuses on **2015 to 2020**.

---

## 6. This is not causal proof

This analysis shows a market pattern.

It does **not** prove that regulation caused the change.

Other factors may also matter:

- Tourism demand
- Seasonality
- COVID-19
- Market saturation
- Economic conditions

---

## Final Assumption

The main pattern is interpreted as a descriptive market signal:

> New host/listing growth peaked in 2015 and slowed afterward, while average prices increased from 2015 to 2020.