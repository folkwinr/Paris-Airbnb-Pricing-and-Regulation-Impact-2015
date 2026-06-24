# Methodology  
## Paris Airbnb Supply & Pricing Shift After 2015

## 1. Analysis Goal

The goal of this analysis is to understand how the Paris Airbnb market changed around the 2015 regulation period.

The main focus is on two market signals:

1. **Supply growth**  
   How many new hosts/listings entered the market each year?

2. **Price movement**  
   How did average prices change before and after 2015?

This analysis is descriptive.  
It shows patterns in the data, but it does not prove that regulation caused the changes.

---

## 2. Data Used

The analysis uses Airbnb listings data for Paris.

The main columns used were:

| Column | Meaning |
|---|---|
| `city` | City name |
| `host_since` | The year when the host started |
| `neighbourhood` | Listing neighbourhood |
| `accommodates` | Number of guests the listing can host |
| `price` | Nightly listing price |

Only Paris listings were used in the final analysis.

After cleaning, the dataset included:

- **64,628 Paris listings**
- **Average nightly price:** €113.20
- **Median nightly price:** €80.00

---

## 3. Data Cleaning

Before analysis, the data was cleaned to make it reliable.

The main cleaning steps were:

1. **Filtered the data for Paris only**  
   Only rows where `city = Paris` were kept.

2. **Converted dates**  
   The `host_since` column was converted into a date format.

3. **Created year column**  
   The year was extracted from `host_since`.

4. **Cleaned price values**  
   Price values were converted into numeric format.

5. **Removed invalid rows**  
   Listings with invalid values were removed, such as:

   - Price equal to 0
   - Guest capacity equal to 0
   - Missing neighbourhood values

This helped avoid misleading averages.

---

## 4. Main Analysis Steps

The analysis was split into four simple parts.

---

### Step 1: Neighbourhood Price Analysis

First, average price was calculated for each Paris neighbourhood.

This helped identify:

- Premium areas
- Affordable areas
- Large price differences across the city

Example result:

| Neighbourhood | Average price |
|---|---:|
| Elysee | €211.37 |
| Menilmontant | €74.96 |

This showed that location is a strong price factor.

---

### Step 2: Capacity Price Analysis

Next, the analysis checked how price changes with guest capacity.

The most expensive neighbourhood was selected, then prices were grouped by `accommodates`.

Example result in Elysee:

| Capacity | Average price |
|---:|---:|
| 2 guests | €155.10 |
| 6 guests | €355.51 |

This showed that larger listings usually have higher prices.

---

### Step 3: Yearly Supply Growth

To study market growth, the `host_since` year was used.

For each year, the analysis counted how many listings were linked to hosts who started that year.

This was used as a simple signal for new host/listing growth.

The key result was:

- **2015 was the peak year**
- **12,147 new hosts/listings** appeared in 2015

After 2015, the number dropped strongly:

| Year | New hosts/listings |
|---:|---:|
| 2015 | 12,147 |
| 2016 | 8,867 |
| 2017 | 4,585 |
| 2018 | 4,294 |
| 2019 | 5,685 |

This showed that supply growth slowed after the 2015 peak.

---

### Step 4: Price Trend Around 2015

The analysis then checked average price movement around 2015.

Instead of using only a simple before-after average, key years were compared.

This was done because:

- 2009 had few listings and a high average price
- 2021 may be affected by COVID-19
- A simple before-after average can hide the real trend

The main price check was:

| Period | Average price change |
|---|---:|
| 2009 to 2014 | €159.64 → €100.25 |
| 2015 to 2020 | €103.65 → €143.52 |

This showed:

- Prices decreased before 2015
- Prices increased from 2015 to 2020

---

## 5. COVID-19 Sensitivity Check

The years 2020 and 2021 may be unusual because of COVID-19.

To check this, the analysis removed 2020 and 2021 and reviewed the trend again.

The result still showed that:

- 2015 was the peak year for new hosts/listings
- New host/listing growth slowed after 2015
- Average price increased from 2015 to 2019

This means the main pattern was already visible before COVID-19.

---

## 6. Why This Method Was Used

A simple before-after comparison was not enough for this project.

Why?

Because Airbnb grew very fast before 2015.  
So, the post-2015 average can still look high, even if growth slowed after the peak.

For this reason, the analysis focused on:

- The **2015 peak**
- The years after the peak
- Price movement from **2015 to 2020**
- A COVID sensitivity check

This gave a clearer view of the market change.

---

## 7. Important Notes

This analysis has some limits.

1. **This is not causal proof**  
   The analysis shows patterns, but it does not prove that regulation caused the change.

2. **`host_since` is not the same as booking history**  
   The year comes from when the host started, not from historical booking prices.

3. **Other factors may affect the market**  
   These include tourism demand, seasonality, COVID-19, economic conditions, and neighbourhood popularity.

4. **Average price can be affected by expensive listings**  
   For this reason, median price was also checked.

---

## 8. Summary of Method

In simple terms, the analysis followed this process:

1. Load Airbnb listings data
2. Filter for Paris
3. Clean price, date, and invalid values
4. Compare prices by neighbourhood
5. Compare prices by guest capacity
6. Count new hosts/listings by year
7. Identify the 2015 market peak
8. Check price movement around 2015
9. Remove COVID years to test the pattern
10. Summarize business insights and limitations

---

## Final Methodology Takeaway

This methodology was designed to answer one main question:

> Did the Paris Airbnb market show a clear change around 2015?

The answer from the data is:

> Yes. New host/listing growth peaked in 2015 and slowed after that. At the same time, average prices increased from 2015 to 2020.

This gives a clear market signal, even though it does not prove regulation was the only cause.