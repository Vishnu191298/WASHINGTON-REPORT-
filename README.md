# WASHINGTON-REPORT-
A Power BI dashboard analyzing Washington State’s EV eligibility, showing CAFV status, top eligible cities, and county-level adoption. Includes electric-range trends by model year and maps highlighting areas with low or unknown eligibility, offering clear insights into EV readiness across the state.
1. Data Import & Initial Understanding

I imported the Washington State EV dataset into Power BI Desktop. The dataset included fields such as:

County / City

EV Type

Battery Electric Range

Model Year

CAFV (Clean Alternative Fuel Vehicle) Eligibility

I began by understanding the structure, verifying column formats, and checking for missing or unknown eligibility data.

2. Data Cleaning & Preparation

To prepare the dataset:

Converted Model Year and Electric Range to numeric types.

Standardized categorical fields like CAFV status.

Handled records where battery range was missing, classifying them as “Eligibility unknown as battery range has not been researched.”

Added a new calculated field to group EVs into Eligible, Not Eligible, and Unknown.

3. Creating Key Measures

I developed essential DAX measures:

% Eligible EVs

% Non-Eligible EVs

% Unknown Eligibility

Sum of Electric Range

Average Electric Range by Model Year

These measures enabled clearer visuals and deeper trend insights.

4. Designing the Report Layout
(A) CAFV Eligibility Overview

I built a donut chart showing:

46.1% Eligible

42.21% Unknown

11.69% Not eligible due to low battery range
This high-level view helped quickly understand statewide eligibility patterns.

(B) Washington State Map Visualization

I used a Filled Map to show:

Which counties have EVs not eligible due to low battery range

Geographic spread of EV adoption patterns across counties such as Benton, Chelan, Clark, Douglas, Franklin, Stevens, and more.
This visually highlighted regions with strong vs. weak EV adoption.

(C) Top 4 Cities Eligible for EVs

I created a bar chart ranking:

Yakima

Yelm

Yarrow Point

Zillah

These were the top four cities with the highest number of eligible EVs.

(D) Electric Range Analysis

I built two visuals:

Sum of Electric Range by Model Year
– Shows total electric range contribution for each year from 1995 to 2024.

Average Electric Range by Model Year
– Highlights battery range improvements across model years (notably increasing after 2015).

This allowed for trend analysis of EV technology advancement.

5. Slicers & Interactivity

To improve user interaction:

Added Model Year slicers

Enabled cross-filtering between eligibility categories, cities, and range visuals

Ensured users can analyze specific model-year performance or eligibility status instantly

6. Formatting & Professional Styling

Used a consistent color theme for EV categories.

Applied clean labels, legends, and tooltips for clear interpretation.

Organized visuals with proper spacing for presentation-quality output.

7. Validation & Quality Checks

Before finalizing:

Verified percentage totals matched dataset records.

Confirmed map locations aligned with Washington counties.

Checked that city rankings accurately reflected eligibility counts.

FINAL OUTCOME

A clean, interactive Power BI dashboard that provides insights into:

EV eligibility status across Washington

Top cities adopting eligible EVs

Battery electric range trends over time

County-level eligibility mapping

Model-year improvements in electric range

This dashboard helps identify adoption patterns, policy impact areas, and future EV infrastructure opportunities.
