# New York Times Books API Integration

**R · REST API · JSON · Data quality**

## Overview
Analyze recurring hardcover fiction titles across four September 2025 bestseller snapshots.

## Analytical workflow
Request dated lists with httr2, parse nested JSON, standardize title and author identifiers, validate dates and ranks, audit missing fields and summarize recurring titles.

## Project files
- [Data 607 NYT API Code base.qmd](Data%20607%20NYT%20API%20Code%20base.qmd) — analysis source.
- See the repository for accompanying rendered reports and any included source data.

## Reproduce
Install httr2, jsonlite, dplyr, tibble, ggplot2 and knitr; set NYT_API_KEY privately in the environment and render with internet access. Never commit credentials.

## Limitations
Four snapshots measure sampled appearances, not sales or total bestseller duration.

*Academic project — DATA 607, CUNY School of Professional Studies.*
