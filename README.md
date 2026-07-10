# Video Game Sales & Market Performance Analysis

## Project Overview

This project analyzes historical video game sales data to identify the factors that drive commercial success across global markets. The objective was to provide data-driven recommendations for Ice, an online video game retailer, to support marketing strategy and product planning for 2017.

The analysis focuses on identifying sales trends, evaluating platform and genre performance, understanding regional customer preferences, and assessing the relationship between review scores and commercial success.

---

## Business Objectives

- Identify the platforms with the strongest market performance.
- Analyze genre popularity across major geographic regions.
- Evaluate how critic and user ratings influence sales.
- Examine the impact of ESRB ratings on purchasing behavior.
- Use statistical analysis to validate key business assumptions.
- Provide actionable recommendations for future marketing campaigns.

---

## Dataset

The dataset contains historical sales and review information for video games released across multiple platforms.

| Column | Description |
|---------|-------------|
| Name | Game title |
| Platform | Gaming platform (PlayStation, Xbox, Nintendo, PC, etc.) |
| Year_of_Release | Release year |
| Genre | Video game genre |
| NA_Sales | North American sales (millions USD) |
| EU_Sales | European sales (millions USD) |
| JP_Sales | Japanese sales (millions USD) |
| Other_Sales | Sales in other regions (millions USD) |
| Critic_Score | Critic review score (0–100) |
| User_Score | User review score (0–10) |
| Rating | ESRB content rating |

**Data Preparation**

- Standardized column names and data types.
- Cleaned missing values and handled "TBD" entries appropriately.
- Created a Total Global Sales feature by aggregating regional sales.
- Validated data quality prior to analysis.

---

## Analytical Workflow

### Data Preparation

- Cleaned and standardized raw data for analysis.
- Converted data types for numerical calculations.
- Engineered new analytical features, including Total Global Sales.
- Addressed missing values using business-appropriate assumptions.

### Exploratory Data Analysis

- Evaluated annual game release trends.
- Identified leading and declining gaming platforms.
- Assessed platform life cycles to determine the most relevant period for forecasting.
- Investigated relationships between review scores and sales performance.
- Analyzed genre popularity and profitability across the market.

### Regional Market Analysis

Developed regional customer profiles for:

- North America
- Europe
- Japan

The analysis included:

- Top-performing platforms
- Highest-selling genres
- Regional purchasing preferences
- ESRB rating distributions
- Differences in customer behavior across markets

### Statistical Analysis

Performed hypothesis testing to evaluate key business questions, including:

- Whether average user ratings differ between Xbox One and PC games.
- Whether Action and Sports games receive significantly different user ratings.

Statistical testing included clearly defined hypotheses, significance levels, and interpretation of results.

---

## Key Findings

- Platform popularity follows clear product life cycles, making recent release trends more valuable than historical performance when forecasting future demand.
- Action, Shooter, and Sports titles generated the highest sales across most global markets, although genre preferences varied by region.
- Critic scores demonstrated a stronger relationship with commercial success than user ratings.
- Customer purchasing behavior differed substantially between North America, Europe, and Japan, highlighting the importance of region-specific marketing strategies.
- ESRB ratings influenced sales differently across geographic markets, suggesting localized product positioning opportunities.

---

## Business Recommendations

Based on the analysis, Ice should:

- Prioritize marketing investment toward recently launched, high-growth platforms.
- Tailor promotional campaigns to regional gaming preferences rather than using a single global strategy.
- Incorporate critic review scores into product selection and merchandising decisions.
- Focus inventory planning on genres with consistent historical sales performance while monitoring emerging platform trends.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
