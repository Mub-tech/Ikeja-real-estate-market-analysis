# Project Methodology

## 1. Project objective

The objective was to turn raw Ikeja property listings into a structured dataset and a set of Excel dashboards that make neighbourhood-level listing patterns, asking prices and land-market signals easier to explore.

## 2. Dataset overview

- **Source:** PropertyPro NG listings
- **Geography:** Ikeja, Lagos, Nigeria
- **Period:** 2022
- **Raw records:** 6,653
- **Retained records:** 6,186
- **Original columns:** 12
- **Neighbourhood categories:** 12

Approximately 93% of the raw records were retained after the project cleaning process.

## 3. Data cleaning and preparation

The preparation workflow included:

1. Reviewing fields, formats and data completeness.
2. Checking for and removing duplicate records.
3. Excluding records expressed as unsuitable rental rates (for example, per day, month or year) where they were not comparable with sale asking prices.
4. Removing non-property entries that did not belong in the analysis.
5. Normalizing USD-denominated asking prices using a project assumption of ₦950 per USD.
6. Screening out asking prices below ₦5 million and above ₦50 billion as implausible for this analysis.
7. Separating title and description information for easier classification.
8. Removing currency and serial fields that were not needed for the analytical output.
9. Creating property-category labels: Land, Commercial and Others.
10. Creating a field to identify listings described as newly built.

The thresholds and exchange-rate assumption are analytical decisions made for this project. They should be revisited if the dataset is refreshed or used for a different purpose.

## 4. Analysis approach

The analysis focused on:

- Listing volume by neighbourhood
- Share of listings by neighbourhood
- Property-category distribution
- Newly built listing counts and proportions
- Asking-price distribution
- Median asking price by property category
- Land listing counts by neighbourhood
- Land asking price per square metre

Median values were emphasized alongside averages because property asking prices are highly skewed. A small number of very expensive listings can pull the mean upward and make it less representative of a typical listing.

## 5. Dashboard design

### Market Overview

This page provides a high-level view of listing volume, neighbourhood concentration, property mix and newly built listings.

### Pricing & Land Analysis

This page focuses on asking-price patterns, differences between land and non-land listings, and land pricing by area.

## 6. Quality and interpretation considerations

- Asking prices are advertised prices, not confirmed transaction prices.
- The source data reflects listings collected in 2022.
- Neighbourhood coverage and listing counts are uneven.
- Property descriptions may be incomplete or inconsistently worded.
- The USD conversion rate is an assumption rather than a verified historical rate for each listing date.
- The price-screening thresholds may exclude genuine outliers as well as errors.

For these reasons, the results are best treated as descriptive market indicators rather than formal valuations.
