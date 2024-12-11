# Crimes Against Women Dashboard - Power BI

This repository contains a Power BI dashboard analyzing crimes against women across Indian states from 2001 to 2021. The dataset includes various crime categories, such as rape, kidnapping, dowry deaths, and domestic violence, providing valuable insights into trends and patterns.

## Dataset Overview

The dataset titled **CrimesOnWomenData** includes the following columns:
- **State**: Name of the state.
- **Year**: Year of the data.
- **Rape**: Number of rape cases reported.
- **Kidnap And Assault**: Number of kidnapping and assault cases.
- **Dowry Deaths**: Number of dowry-related deaths.
- **Assault against women**: Total cases of assault against women.
- **Assault against modesty of women**: Cases of assault specifically targeting modesty.
- **Domestic violence**: Cases of domestic violence reported.
- **Women Trafficking**: Cases of trafficking of women.

## Key Features of the Dashboard

1. **Crime Trend Analysis**:
   - Line chart visualizing yearly trends in various crime categories.
   - Percentage growth in crimes year-over-year.

2. **State-wise Comparison**:
   - Bar and column charts comparing the total number of crimes by state.
   - Highlight states with the highest and lowest crime rates.

3. **Crime Category Breakdown**:
   - Pie and donut charts for visualizing the proportion of each crime type in total crimes.

4. **Heatmap**:
   - Heatmap showing crime intensity across states.

5. **Crime Growth Metrics**:
   - DAX measures to calculate yearly crime percentage growth.
   - KPI cards to highlight significant metrics.

6. **Interactive Features**:
   - Filters for selecting specific years, states, and crime types.
   - Drill-through functionality for deeper insights.

## DAX Measures

This dashboard employs custom DAX measures for advanced analytics:
- **Total Crimes**: Aggregates all crime categories.
- **Yearly Crime Growth (%)**: Calculates percentage growth in crimes year-over-year.
- **Crime Intensity Score**: Weighted score based on crime severity.
- **Category Distribution**: Displays the proportional contribution of each crime type.

## Date Table

A custom date table is included, spanning the years 2001 to 2021. The table supports time intelligence features for analyzing data over different periods.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CrimesAgainstWomenDashboard.git
