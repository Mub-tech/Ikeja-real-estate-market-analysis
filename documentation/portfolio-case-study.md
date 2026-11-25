# Ikeja Real Estate Market Analysis | Portfolio Case Study

## Executive summary

I analysed 6,653 online property listings across Ikeja, Lagos (2022), cleaned the dataset to 6,186 usable records (about 93% retained), and built an interactive Excel dashboard to explore listing concentration, property mix, asking-price patterns, newly built properties and land pricing.

The goal was to turn a large, messy listing dataset into practical market questions that a property seeker, analyst or business stakeholder could explore without manually reviewing thousands of records.

## Project at a glance

| | |
|---|---|
| **Project type** | Real estate market analysis |
| **Location** | Ikeja, Lagos, Nigeria |
| **Dataset period** | 2022 listings |
| **Source** | PropertyPro NG listings |
| **Tool** | Microsoft Excel |
| **Records analysed** | 6,186 cleaned listings from 6,653 raw rows |
| **Deliverables** | Data-cleaning workflow, analysis, two interactive dashboard pages, insights and recommendations |

## The business questions

1. Where are listings concentrated across Ikeja neighbourhoods?
2. What property types dominate each neighbourhood?
3. How does newly-built inventory vary by area?
4. How do asking prices vary across locations and categories?
5. Where is land-listing supply concentrated?
6. What do land prices per square metre suggest, and how could a buyer estimate a plot budget?

## Workflow

### 1. Data preparation
- Removed duplicate records.
- Excluded rental-rate rows expressed per square metre, year, day or month where they were not comparable to sale asking prices.
- Converted USD-denominated asking prices using an assumed exchange rate of **₦950/USD**.
- Removed non-property items and filtered out asking prices below **₦5m** or above **₦50bn**.
- Split combined Title and Description fields for better structure.
- Removed currency and serial columns not required for the analysis.

### 2. Classification and analysis
Created practical property groupings for **Land**, **Commercial**, and **Others** (residential and unclassified records). Analysed neighbourhood listing share, category mix, newly-built counts and rates, price distributions, land supply, and land asking price per square metre.

### 3. Dashboard design
Built two Excel dashboard pages supported by calculation sheets and cleaned data.

- **Market Overview:** listing concentration, property mix, newly-built inventory and neighbourhood comparisons. Interactive filters include property type, newly-built status, price range and neighbourhood.
- **Pricing & Land Analysis:** asking-price comparisons, land inventory and price-per-square-metre analysis. Includes a neighbourhood selector and plot-size input for a land-budget scenario.

Dashboard input cells drive the linked calculations, charts and insight text. The intent was to make the workbook exploratory rather than a static report.

## Key findings

- **Listing concentration:** GRA accounts for about **28%** of listings. GRA, Other Ikeja and Adeniyi Jones together account for around **60%**.
- **Newly-built inventory:** GRA has the largest count (**352**). Adeniyi Jones has the highest newly-built share at **29%**, compared with **21%** in GRA.
- **GRA property mix:** approximately **66%** residential/Other, **32%** land and **2%** commercial.
- **Price distribution:** overall median asking price is about **₦150m**, while the mean is approximately **₦526m**. The gap highlights the influence of high-priced listings and why the median is useful for typical-price comparisons.
- **Neighbourhood comparison:** Awolowo Way has a median asking price around **₦220m**, versus about **₦200m** for GRA; the ranges overlap, so this should not be interpreted as a definitive price ranking.
- **Land premium:** median land asking price is about **₦300m**, compared with **₦130m** for non-land listings (roughly 2.3×).
- **Land supply:** GRA has the most land listings (**548**); Omole has the fewest (**15**).
- **Land price per sqm:** the overall median is approximately **₦190k/sqm**, with the middle 50% around **₦147k–₦265k/sqm**.
- **Budget scenario:** a 600 sqm plot at the median rate gives an indicative estimate of **₦114m**, with a middle-50%-based scenario range of roughly **₦88m–₦159m**.

## Recommendations

1. Use GRA as a starting point when breadth of listing choice is important, then compare other neighbourhoods based on the buyer's requirements.
2. For newly-built stock, compare both the total inventory and share of listings; Adeniyi Jones stands out by share in this dataset.
3. Use medians and distribution ranges alongside averages to avoid being misled by a few expensive listings.
4. Compare land on price per square metre, while checking plot size, location and property details individually.
5. Break the aggregated “Other Ikeja” category into smaller locations where possible to improve geographic insight.

## What this project demonstrates

- Excel data cleaning and quality checks
- Exploratory analysis and descriptive statistics
- KPI calculations and interactive filters
- Dashboard construction and data storytelling
- Translating analysis into business interpretation and recommendations
- Communicating limitations and avoiding unsupported conclusions

## Limitations and responsible interpretation

This dataset contains **2022 online asking prices**, not verified transaction prices, and it should not be treated as a current valuation. Listing coverage may be biased or uneven. The aggregated “Other Ikeja” category includes smaller areas. Comparisons are descriptive and do not account for title, building condition, access, zoning, exact location, negotiation or other property-specific factors. The ₦950/USD conversion is an assumption used for consistency.

## Project repository

[Open the GitHub repository](https://github.com/Mub-tech/Ikeja-real-estate-market-analysis)

> **Assets note:** The workbook and dashboard screenshots are described in the repository but still need to be uploaded as binary files. Add them to an `assets/` or `project-files/` folder and update this case study with preview images once uploaded.

