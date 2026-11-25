# Ikeja Real Estate Market Analysis

An Excel-based analysis of residential, commercial and land property listings in Ikeja, Lagos, Nigeria, using listings collected from PropertyPro NG for 2022.

## Project overview

The project examines listing distribution, asking-price patterns, property categories, newly built properties and land pricing across Ikeja neighbourhoods. It follows an end-to-end spreadsheet workflow: data cleaning, preparation, exploratory analysis, KPI development and interactive dashboard reporting.

**Tools:** Microsoft Excel

## Business questions

- Which Ikeja neighbourhoods account for the largest share of property listings?
- How do asking prices vary across property categories?
- Where are land listings concentrated, and how do land prices per square metre differ?
- What share of listings are classified as newly built?
- What useful market signals can be drawn from the listing data?

## Dataset and preparation

The working dataset contained 6,653 raw records and 12 original columns. After cleaning, 6,186 records were retained for analysis, representing approximately 93% of the original records.

Preparation included duplicate checks, removal of unsuitable rental-rate records and non-property entries, currency normalization for USD-denominated listings using an assumed exchange rate of ₦950 per USD, screening of implausible asking prices, and creation of analysis fields for property category and newly built status.

The price screening thresholds were below ₦5 million and above ₦50 billion. These are project-specific data-quality rules, not universal definitions of valid property prices.

## Dashboard

The workbook was designed around two views:

1. **Market Overview:** listing distribution, neighbourhood comparisons, property mix and newly built listings.
2. **Pricing & Land Analysis:** asking-price comparisons, land listing distribution and land price-per-square-metre analysis.

## Selected findings

- GRA had the largest listing count, with 1,716 records.
- Other Ikeja accounted for 1,158 records, followed by Adeniyi Jones with 820.
- The three largest categories represented about 60% of the cleaned dataset.
- The overall median asking price was approximately ₦150 million, compared with a mean of approximately ₦526 million, indicating a strongly right-skewed price distribution.
- The median asking price for land listings was approximately ₦300 million, compared with approximately ₦130 million for non-land listings.
- GRA had the highest absolute count of newly built listings (352), while Adeniyi Jones had a higher newly built share, approximately 29%.

See [business insights](documentation/business-insights.md), [methodology](documentation/project-methodology.md) and [recommendations](documentation/recommendations.md) for details.

## Important limitations

This analysis describes online asking listings, not verified sale transactions or formal property valuations. The dataset represents 2022 listings and should not be interpreted as a current 2026 market valuation. Listing coverage may be uneven across neighbourhoods, property descriptions can be inconsistent, and the USD conversion uses an assumed rate of ₦950 per USD.

The aggregated **Other Ikeja** category is not a single neighbourhood. Results should be used as directional market signals rather than investment or valuation advice.

## Repository contents

- `documentation/project-methodology.md`: data preparation and analytical approach
- `documentation/business-insights.md`: key findings and interpretation
- `documentation/recommendations.md`: practical recommendations and next steps

The Excel workbook, dashboard PDF and dashboard screenshots are not included in this initial documentation upload. They can be added when the source files are available.
