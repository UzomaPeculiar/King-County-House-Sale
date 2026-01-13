# King-County-Washington-House-Sales-Dashboard

## Project Overview
This project involves creating an interactive Tableau dashboard to analyze house sales data in King County, Washington, focusing on price trends, property distributions, and key factors influencing home values. The dashboard visualizes daily average house prices over time, geographic distributions via a map, histograms for house prices, bedrooms, and bathrooms, and a heatmap comparing property views against conditions with associated average prices. Users can apply filters for month/day, year built, square footage of living space, and lot size to explore trends, such as price fluctuations in specific periods (e.g., September 2014), spatial variations across neighborhoods, and correlations between property features like bedrooms/bathrooms and overall market dynamics. Built using publicly available real estate sales data, this dashboard uncovers patterns like higher average prices in areas with better views or conditions, providing insights for buyers, sellers, and real estate professionals to understand market behavior in King County.

<div class='tableauPlaceholder' id='viz1768268507387' style='position: relative'><noscript><a href='#'><img alt='HouseSalesDashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ki&#47;KingCountyHouseSalesDashboard_v2025_2&#47;HouseSalesDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='KingCountyHouseSalesDashboard_v2025_2&#47;HouseSalesDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ki&#47;KingCountyHouseSalesDashboard_v2025_2&#47;HouseSalesDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

## Data Sources
- **Primary Dataset**: House sales data from King County, Washington, sourced from https://github.com/mochen862/king-county-house-sales/blob/main/HouseData.xlsx
  - Contains details such as sale date, price, bedrooms, bathrooms, square footage (living and lot), year built, condition, view rating, and geographic coordinates (latitude/longitude) for mapping.

## Tools Used
- **Tableau**: Dashboard creation, visualization, interactivity, and mapping (using Mapbox/OpenStreetMap integration).

## Data Cleaning/Preparation
1. **Additional Steps**:
   - Converted date fields to extract month, day, and year for time-based filtering; created calculated fields for average prices, binned distributions (e.g., price ranges, bedroom/bathroom counts), and heatmap aggregations; geocoded locations for map visualization.

## Exploratory Data Analysis (EDA)
Key questions explored:
1. How do daily average house prices trend over a selected month? (Line chart for September 2014 shows fluctuations around 400K-600K, with potential dips mid-month possibly due to market volatility.)
2. Where are house sales concentrated geographically, and how do prices vary by location? (Choropleth map highlights higher-density areas like Seattle with darker shades indicating higher price clusters, extending to suburbs like Tacoma and Olympia.)
3. What is the distribution of house prices? (Histogram reveals a peak in the 200K-600K range, with a right-skew toward higher-end properties up to 1.4M+.)
4. How do property views and conditions impact average prices? (Heatmap shows premium for "Excellent" views (up to 1.27M average) versus "None" (around 512K), with conditions from "Poor" to "Very Good" correlating to increasing values.)
5. What are the common distributions for bedrooms and bathrooms? (Histograms indicate most homes have 2-4 bedrooms (peaking at 3) and 1-2.5 bathrooms, with frequencies dropping for larger configurations.)
Overall insights: King County house prices average around 500K-700K in the analyzed period, with strong influences from location, views, and condition. Filtering reveals opportunities in mid-range properties, while trends suggest seasonal or daily variations worth monitoring for investment decisions.

Link to Tableau Public [https://public.tableau.com/views/KingCountyWashingtonHouseSales/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link](https://public.tableau.com/views/KingCountyHouseSalesDashboard_v2025_2/HouseSalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
