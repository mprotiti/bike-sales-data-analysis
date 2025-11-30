## bike-sales-data-analysis
This project focuses on a complete data analysis and visualization workflow executed entirely within Microsoft Excel. The goal was to take raw customer data, clean it, analyze key demographics, and build an interactive dashboard to explore factors influencing bicycle purchasing decisions.
## Core Methodology & Key Tasks:
# 1. Data Preparation and Cleaning:
    ◦ The raw data was copied to a separate working sheet to preserve the original dataset.
    ◦ Duplicate rows were identified and removed to ensure data quality.
    ◦ Categorical data was standardized; for instance, marital status ('m'/'s') was updated to 'married'/'single' and gender ('m'/'f') to 'male'/'female' to improve usability of the dashboard.
    ◦ The income column was formatted consistently as currency.
# 2. Feature Engineering (Age Brackets):
    ◦ A new derived column, Age Brackets, was created using complex nested IF statements. This grouping (e.g., adolescent, middle age, old) was necessary because visualizing the entire range of individual ages (25 to 89) on a chart would be overly messy and difficult to interpret.
# 3. Visualization and Analysis (Pivot Tables):
    ◦ Pivot Tables were used as the foundation for the dashboard visualizations.
    ◦ Average Income Analysis: A visualization was built to compare the average income of bike purchasers versus non-purchasers, broken down by gender. Analysis showed that individuals who bought bikes generally had a higher average income.
    ◦ Commute Distance Analysis: A chart was created to understand the relationship between customer commute distance and purchase quantity.
    ◦ Age Bracket Purchasing Trends: A visualization highlighted bike purchase counts across the new Age Brackets, revealing that the middle-aged group (31–54) purchased the highest number of bikes.
# 4. Interactive Dashboard Development:
    ◦ The three main visualizations were copied to a dedicated dashboard sheet.
    ◦ The dashboard was polished by removing Excel grid lines and adding a clear header ("Bike Sales Dashboard").
    ◦ Interactive Slicers were added for Marital Status, Region, and Education. These slicers were linked to all three Pivot Charts, allowing a user to instantly filter the entire dashboard by various demographic combinations.
