# 2025 Federal Election: Fact-Check & Swing Analysis

## Overview

This project investigates changes in Australian federal election voting patterns between 2022 and 2025. It independently fact-checks the reported claim that minor parties and independents collectively received more first-preference votes than the Coalition in the 2025 federal election.

The analysis combines Australian Electoral Commission (AEC) election data with Australian Bureau of Statistics (ABS) Census data to:

-   Verify the national voting shift using raw election data
-   Determine whether the trend is consistent across different electorate types
-   Explore the demographic characteristics of an electorate experiencing a strong swing

**Full Report:** [View PDF Report](report/australian_election_analysis.pdf)

------------------------------------------------------------------------

## Research Questions

This project explores three key questions:

1.  Does the reported national first-preference vote share hold when recalculated from raw AEC data?
2.  Is the shift away from the Coalition consistent across electorates, or only visible at the national level?
3.  What demographic characteristics describe an electorate with a strong voting shift?

------------------------------------------------------------------------

## Key Findings

-   Minor parties and independents surpassed the Coalition in 2025 first-preference votes.
-   Voting shifts occurred across all electorate classifications.
-   Monash showed a strong swing linked with distinct demographic characteristics.

## Analytical Workflow

### 1. Election Data Processing

-   Combined AEC first-preference vote data from the 2022 and 2025 federal elections
-   Standardised party classifications into:
    -   Labor
    -   Coalition
    -   Minor parties and independents
-   Calculated national and electorate-level vote shares

### 2. Spatial Analysis

-   Compared electorate-level vote-share changes between elections
-   Joined AEC electorate boundaries with ABS Census data using spatial methods
-   Analysed demographic patterns by electorate

### 3. Demographic Analysis

Examined the Monash electorate using ABS Census variables including:

-   Median weekly family income
-   Median mortgage repayments
-   Age distribution
-   Gender distribution

------------------------------------------------------------------------

## Tools & Technologies

### Programming & Analysis

-   R
-   Tidyverse

### Spatial Analysis

-   `sf`
-   Coordinate transformations
-   Spatial joins

### Reporting

-   Quarto

### Data Sources

-   Australian Electoral Commission (AEC) election results
-   AEC electoral boundaries and classifications
-   Australian Bureau of Statistics (ABS) 2021 Census

------------------------------------------------------------------------

## Skills Demonstrated

-   Data cleaning and transformation
-   Classification logic and aggregation
-   Fact-checking using public datasets
-   Spatial data analysis
-   Geospatial joins
-   Demographic profiling
-   Data visualisation
-   Evidence-based reporting
-   Reproducibility

------------------------------------------------------------------------

## Project Context

This project was developed as part of postgraduate Business Analytics coursework at Monash University.
