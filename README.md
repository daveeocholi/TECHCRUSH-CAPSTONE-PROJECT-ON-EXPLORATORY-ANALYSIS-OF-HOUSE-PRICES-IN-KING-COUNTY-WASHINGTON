# TECHCRUSH-CAPSTONE-PROJECT-ON-EXPLORATORY-ANALYSIS-OF-HOUSE-PRICES-IN-KING-COUNTY-WASHINGTON

## Project Title
**Capstone Project: Exploratory Data Analysis of Residential House Prices in King County, Washington**

---

## Project Objectives

- Identify key features influencing house pricing (e.g., size, location, condition)
- Examine seasonal and geographical price trends to inform sales timing and marketing
- Assess the pricing impact of renovations, waterfront access, and architectural design
- Build a dynamic, interactive dashboard using Microsoft Power BI for strategic decision-making

---

## Dataset Used

- **Source:** King County House Sales Dataset  
- **Access:** [Kaggle via OneDrive Link](https://1drv.ms/x/c/1ff33ac6bbc8d182/EeDV-5FO_05PhZT8Ea-mbfoBCqK--wSF3GRzP0VgnEPZlw?e=RGhhtA)  
- **Record Count:** 21,613 property listings  
- **Timeframe:** 2014–2015  
- **Attributes:** Price, bedrooms, bathrooms, living area (sqft), location, year built, year renovated, waterfront status, condition, architectural grade, and more

---

## Key Questions Explored

- What features have the most significant influence on house pricing?
- How does house size or renovation status affect price?
- Do location and seasonality significantly impact pricing?
- Which zones (cities or zip codes) yield the highest returns?
- Are there consistent pricing premiums for waterfront or recently renovated properties?
- How can real estate stakeholders use data to improve valuation accuracy?

---

## Process

### Data Cleaning & Preparation (Excel)

- Removed null, duplicate, and extreme outlier values
- Standardized date and numeric formats
- Created calculated fields (e.g., Price per Square Foot, Renovation Flag)
- Grouped/renamed variables for clarity:
  - `sqft_living → House Size (Small/Medium/Large)`
  - `waterfront → Waterfront (Yes/No)`
  - `grade → Architecture Quality`
  - `condition → Habitability`

### Exploratory Data Analysis (SQL + Excel)

- Used **SQL** for statistical summaries: average, median, mode
- Employed **PivotTables** in Excel to:
  - Segment listings by city, size, renovation status
  - Track monthly pricing trends
  - Explore feature-price relationships

---

## Dashboard Building (Power BI)

### Setup & Modeling

- Imported cleaned dataset into Power BI
- Verified data types and formats
- Created calculated columns and DAX measures:
  - `Average Price`
  - `Waterfront Property %`
  - `Listings by House Size`
  - `Average Living Area`
  - `City-wise Price Metrics`

### Dashboard Design

| Visual Type        | Purpose                                                      |
|--------------------|--------------------------------------------------------------|
| KPI Cards          | Summary of key metrics (price, volume, waterfront %)         |
| Filled Map         | Price distribution across zip codes                          |
| Clustered Bar Chart| Price by city, house size, renovation status                 |
| Stacked Column     | Bedroom count by renovation/size                             |
| Slicers            | Filters for city, condition, renovation, house features      |

### Design Specifications

- **Color Theme:** Navy (#002147), Sky Blue (#5DADEC), Grey (#A9A9A9), White (#FFFFFF)  
- **Typography:** Segoe UI and Calibri  
- **Layout:** Grid-based design with interactive slicers and tooltips for usability

---

## Dashboard Preview

> ![King_County_Housing_Analysis 1 _Page_1](https://github.com/user-attachments/assets/75264bcf-a87c-41ed-8f49-759dcd54d9b9)
> *City-level pricing, waterfront effects, renovation impact*

> ![King_County_Housing_Analysis 1 _Page_2](https://github.com/user-attachments/assets/fca20379-528d-4dbe-b84c-f68311572172)
> *Geographic map, pricing by region, design and architecture influence*

> ![King_County_Housing_Analysis 1 _Page_3](https://github.com/user-attachments/assets/a1392a7f-7a26-4568-914c-9d1a830500aa)
> *Correlation analysis: feature vs. price impact*

---

## Recommendations and Insights

### Key Takeaways

- **Seattle, Bellevue, and Kirkland** are high-value zones with premium pricing
- **Waterfront properties** and **renovated homes** show significantly higher average prices
- **House size**, **architectural grade**, and **condition** are top pricing factors
- **Seasonal trends** suggest better returns during warmer months
- **Smaller homes** are concentrated in lower-priced zones like Kent and Auburn

### Suggested Actions

- **For Agents & Sellers:** Emphasize recent renovations and premium features in listings  
- **For Investors:** Prioritize areas like Seattle and Bellevue, focus on medium-to-large homes with potential for renovation  
- **For Developers:** Design homes that meet high architectural and livability standards to maximize price

---

## Conclusion

This capstone project demonstrates the value of a structured data analysis workflow in uncovering actionable insights for real estate decision-making. By combining Excel, SQL, and Power BI, we transformed raw housing data into an interactive dashboard that delivers meaningful, location-aware pricing intelligence. This analysis provides a practical framework for investors, realtors, and homeowners to:
- Improve valuation accuracy
- Optimize renovation decisions
- Target marketing based on data-backed trends

---

## Project Deliverables

- `cleaned_king_county_dataset.xlsx`: Preprocessed dataset used in Power BI
- `king_county_dashboard.pbix`: Interactive dashboard file
- `dashboard-previews/`: Screenshots of key visualizations
- `README.md`: Project documentation

---

## Author

**Dave the Analyst**  
Capstone Project – TechCrush Data Analytics Bootcamp  
Connect with [Dave on LinkedIn](https://www.linkedin.com/in/david-ocholi/)
