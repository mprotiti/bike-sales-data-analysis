# Core Methodology & Key Tasks

## 1. Data Preparation & Cleaning

Copied the raw dataset to a separate working sheet to preserve the original data.

Identified and removed duplicate rows for data quality.

Standardized categorical values:

m / s → married / single

m / f → male / female

Formatted the Income column consistently as currency for clearer interpretation.

## 2. Feature Engineering: Age Brackets

Created a new derived column: Age Brackets.

Used nested IF formulas to classify ages into groups (e.g., adolescent, middle age, old).

This grouping solved the readability issue of visualizing the full age range (25–89) directly on charts.

## 3. Visualization & Analysis (Pivot Tables)

Built three main analyses using Pivot Tables:

🔹 Average Income Analysis

Compared the average income of bike purchasers vs. non-purchasers.

Segmented by gender.

Insight: Bike purchasers generally had higher average incomes.

🔹 Commute Distance Analysis

Charted the relationship between commute distance and purchase count.

Helped identify commute patterns of likely buyers.

🔹 Age Bracket Purchasing Trends

Visualized purchase distribution across Age Brackets.

Key finding: Middle-aged individuals (31–54) purchased the most bikes.

## 4. Interactive Dashboard Development

Moved the three Pivot Charts to a dedicated dashboard sheet.

Cleaned the layout by removing gridlines and adding a clear header: “Bike Sales Dashboard”.

Added and linked Slicers for:

Marital Status

Region

Education

All slicers were synchronized across all charts, enabling fully interactive filtering.

✅ Final Deliverables

Cleaned dataset

Feature-engineered fields (Age Brackets)

Pivot-table-based charts

Fully interactive Bike Sales Dashboard

Insights that connect demographics to purchasing decision
