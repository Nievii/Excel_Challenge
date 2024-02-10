# Crowdfunding Data Analysis

This repository contains the analysis of a database with 1,000 sample crowdfunding projects from platforms like Kickstarter and Indiegogo. The goal is to uncover hidden trends and insights by organizing and analyzing the provided dataset.

## Before You Begin

1. **Create a New Space:**
   - Create a new space for this project named `excel-challenge` in Dropbox or Google Drive.
   - Do not add this challenge to an existing repository.

2. **Store Excel Workbooks:**
   - Store your Excel workbooks in the new space.
   - Create a shareable link for submission.

## Files

- [Module 1 Challenge files](#) (Links to an external site.)

## Instructions

### Conditional Formatting

1. Apply conditional formatting to the `Outcome` column:
   - Different colors for successful, failed, canceled, and live campaigns.
2. Apply conditional formatting to the `Percent Funded` column:
   - Use a three-color scale from dark red (0) to green (100) to blue (200).

### Column Creation

1. Create six new columns:
   - `Percent Funded`
   - `Average Donation`
   - `Parent Category`
   - `Sub-Category`
   - `Date Created Conversion`
   - `Date Ended Conversion`

### Pivot Tables and Stacked Column Charts

#### Category Stats

1. Create a new sheet with a pivot table:
   - Analyze the initial worksheet to count successful, failed, canceled, and live campaigns per category.
2. Create a stacked-column pivot chart:
   - Filterable by country based on the table.

#### Subcategory Stats

1. Create a new sheet with a pivot table:
   - Analyze the initial sheet to count campaigns per sub-category.
2. Create a stacked-column pivot chart:
   - Filterable by country and parent category based on the table.

#### Outcomes Based on Launch Date

1. Create a new sheet with a pivot table:
   - Columns of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and years.
2. Create a pivot-chart line graph visualizing the new table.

### Report in Microsoft Word

Answer the following questions in a cohesive written analysis:

1. Given the data, what are three conclusions about crowdfunding campaigns?
2. What are the limitations of this dataset?
3. What additional tables and/or graphs could be created, and what value would they provide?

### Crowdfunding Goal Analysis

1. Create a new sheet with 8 columns:
   - Goal
   - Number Successful
   - Number Failed
   - Number Canceled
   - Total Projects
   - Percentage Successful
   - Percentage Failed
   - Percentage Canceled
2. Populate the table with COUNTIFS() formula.
3. Create a line chart showing the relationship between a goal amount and success, failure, or cancellation.

### Statistical Analysis

1. Create a new worksheet with columns for backers of successful and unsuccessful campaigns.
2. Evaluate the mean, median, min, max, variance, and stdev using Excel formulas.
3. Provide a brief justification of whether the mean or median better summarizes the data.
4. Determine if there is more variability with successful or unsuccessful campaigns and justify the reasoning.

## Requirements

### Conditional Formatting (10 points)

- Applied appropriately to the `Outcome` column (5 points)
- Applied appropriately to the `Percent Funded` column (5 points)

### Column Creation (10 points)

- Six new columns correctly created.

### Pivot Tables and Stacked Column Charts (15 points)

#### Category Stats

- Correctly created a pivot table (7.5 points)
- Correctly created a stacked column pivot chart (7.5 points)

#### Subcategory Stats

- Correctly created a pivot table (7.5 points)
- Correctly created a stacked column pivot chart (7.5 points)

#### Outcomes Based on Launch Date

- Correctly created a pivot table (7.5 points)
- Correctly created a pivot chart line graph (7.5 points)

### Written Report (20 points)

- Cohesive written analysis drawing three conclusions (10 points)
- Stating limitations of the dataset and suggesting additional tables or graphs (10 points)

### Crowdfunding Goal Analysis (10 points)

- Computed calculations of percentages for projects per goal range (5 points)
- Created a line chart showing the relationship between goal amount and success, failure, or cancellation (5 points)

### Statistical Analysis (20 points)

- Computed calculations of mean, median, min, max, variance, and stdev using Excel formulas (15 points)
- Brief and compelling justification of whether the mean or median better summarizes the data (5 points)

