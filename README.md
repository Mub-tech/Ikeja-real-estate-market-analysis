# Ikeja Real Estate Market Analysis

An Excel-based analysis of 2022 PropertyPro NG property listings across Ikeja, Lagos, Nigeria. This project explores listing concentration, property mix, asking prices, newly built properties and land-market patterns.

## Project overview

The project uses an end-to-end Microsoft Excel workflow: data cleaning, preparation, analysis, KPI calculations and interactive dashboard reporting.

**Tool:** Microsoft Excel

## Business questions

- Which area categories account for the highest share of listings?
- How does property type and newly-built status vary by area?
- How do asking prices differ by category and neighbourhood?
- Where is land listing supply concentrated?
- How can land asking prices be compared using price per square metre?

## Dataset and cleaning

- Raw records: 6,653
- Cleaned records: 6,186
- Retention: approximately 93%
- 12 neighbourhood categories

Cleaning included duplicate removal, dropping per-square-metre/year/day/month rental-rate records, converting USD listings using an assumed ₦950/USD, removing non-property items, screening prices outside ₦5m–₦50bn, splitting Title and Description, and removing Currency and serial columns.

Property categories were defined as:
- **Land:** listings classified as land
- **Commercial:** hotel, warehouse, office, shops, factory, filling station, school/hospital and commercial buildings
- **Others:** residential and unclassified listings

## Dashboards

### Dashboard 1: Market Overview
Answers Q1–Q4 and focuses on listing concentration, property mix, newly built stock and neighbourhood-level overview. Filters include property type, newly built status, minimum/maximum price and neighbourhood.

### Dashboard 2: Pricing & Land
Answers Q5–Q8, emphasizing asking-price comparisons, land supply and price-per-square-metre insights. Includes a neighbourhood filter and plot-size input for an estimated land-budget scenario.

Dashboard calculations and written takeaways are linked to the Clean Data and Calc sheets. The dashboard's amber input cells are intended to be changed by the viewer; related tiles, charts and insights recalculate.

## Selected findings

- GRA holds 28% of the 6,186 listings. GRA, Other Ikeja and Adeniyi Jones together account for about 60%.
- GRA leads in newly built listing count (352), while Adeniyi Jones has the highest newly built share (29% versus 21% in GRA).
- GRA's listing mix is approximately 66% residential/Other, 32% land and 2% commercial.
- Median asking price is about ₦150m versus a mean of ₦526m, reflecting skew from high-value listings.
- Awolowo Way has the highest area median asking price in the notes (₦220m), compared with GRA at ₦200m; their intervals overlap.
- Land median asking price is ₦300m versus ₦130m for non-land, around 2.3 times higher.
- Land listing supply is deepest in GRA (548 listings) and lowest in Omole (15).
- Land median asking price per sqm is approximately ₦190k; the middle 50% is roughly ₦147k–₦265k. A 600 sqm budget scenario at the median is about ₦114m (range about ₦88m–₦159m).

## Business interpretation

See [business insights](documentation/business-insights.md), [methodology](documentation/project-methodology.md), and [recommendations](documentation/recommendations.md).

## Limitations

These are 2022 asking prices, not confirmed sale prices or current market values. Online listing coverage may be uneven. “Other Ikeja” is an aggregated group (about 19% of listings), containing smaller areas such as Toyin Street, Oba Akran, Mangoro and others. Median and price-per-square-metre comparisons remain descriptive and do not control for title, condition, access, zoning or other property attributes.

## Repository contents

- `documentation/project-methodology.md`
- `documentation/business-insights.md`
- `documentation/recommendations.md`

**Dashboard workbook and screenshots:** These binary project assets still need to be added to the repository. The dashboard workbook is the source of the charts and interactive inputs described above.
