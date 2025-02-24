# FDA Adverse Events Analysis - Power BI Project

## Overview

This Power BI project provides a comprehensive analysis of adverse events reported to the FDA, focusing on food products and related industries. The dashboard is designed to visualize the distribution of health-related incidents across different sectors, age groups, and outcomes, offering clear insights into safety concerns in consumables and cosmetic products.

![FDA Adverse Events Dashboard](https://eu-images.contentstack.com/v3/assets/blt14ac89070d5e4751/blt42631236be098804/6639380e60bdf4dd8c573573/Apple_(1).png?width=1280&auto=webp&quality=95&format=jpg&disable=upscale)

## Data Source

The dataset used for this analysis comes from the FDA's CAERS (Center for Food Safety and Applied Nutrition Adverse Event Reporting System). Each entry in the dataset corresponds to an individual adverse event, documenting the product involved, symptoms reported, and the outcomes experienced by the affected individuals.

## Key Features

### 1. Total Reports and Industry Breakdown
- Displays the total number of reports (90,614)
- Highlights 38 different industry categories

### 2. Outcome Analysis by Age Group
- Visualizes outcomes across different age groups: Adults, Children, Elderly, Infants, Toddlers, Teenagers, and Young Adults
- Identifies the most common outcomes for each group

### 3. Outcome Analysis by Industry
- Bar chart showing the distribution of reports across various industry categories
- Cosmetics and Foods/Dietary Supplements lead in volume

### 4. Event Outcome Distribution
- Pie chart revealing the percentage of outcomes:
  - Non-serious injuries/illness (30.96%)
  - Other serious important medical events (30.65%)
  - Visited a healthcare provider (19.22%)
  - Hospitalization (11.68%)
  - Visited an ER (7.49%)

### 5. Filters
- Gender filter
- Outcome filter
- Product role filter (Concomitant, Suspect)

## Insights

- Adults are the most affected demographic in nearly all outcome categories
- Non-serious injuries or illnesses are the most commonly reported, followed by serious medical events
- The Cosmetics industry shows the highest number of reported incidents, with Foods/Dietary Supplements close behind
- The dashboard's filtering options provide flexibility to focus on gender, specific outcomes, and product roles for more detailed analysis

## How to Use

1. Open the Power BI file (`FDA_Adverse_Events_Analysis.pbix`) in Power BI Desktop
2. Apply filters to narrow down the data by gender, outcomes, or product role
3. Hover over the visuals to access more detailed data
4. Click on chart elements to apply cross-filtering across the visuals

## Future Enhancements

- Implement time-series analysis to reveal trends over the years
- Add a more granular breakdown of specific symptoms associated with adverse events
- Include geographic data for regional analysis if it becomes available

## Requirements

- Power BI Desktop (latest version recommended)
- Windows 8.1 or later

