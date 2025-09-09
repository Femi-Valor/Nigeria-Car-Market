# Nigeria-Car-Market-Analysis-

### Project Overview
The Nigerian automotive market is one of the largest in Africa, with millions of vehicles being traded every year. A significant percentage of cars are imported, and the preferences of buyers vary across brands, models, colors, and performance metrics. This project seeks to provide data-driven insights into the Nigerian car market using a Power BI dashboard that highlights:

* Average vehicle metrics such as price, mileage, horsepower, and engine size.

* Popularity of car brands and models across Nigeria.

* Color preferences among Nigerian car buyers.

* Driver transmission choices (Automatic vs. Manual).

* Market segmentation between brand new, foreign used (Tokunbo), and Nigerian used cars.

This analysis is intended to serve stakeholders including car dealers, importers, policymakers, and buyers who require deeper market intelligence to make better-informed decisions.

### Problem Statement
The Nigerian car market, while vibrant, suffers from information asymmetry. Buyers often face uncertainty regarding pricing, mileage, performance, and long-term value of vehicles, while sellers and importers struggle to align inventory with buyer preferences.

* Some of the challenges include:

* Lack of reliable market averages for price, mileage, and engine performance. 

* Limited knowledge about consumer preferences for brand, color, and transmission type.

* Heavy reliance on foreign imports without proper market segmentation insights.

* Policymakers lacking sufficient data-driven evidence to regulate vehicle importation and promote sustainable alternatives.

This project addresses these issues by building a comprehensive market analysis dashboard, backed by real vehicle data, to uncover trends and recommend strategies for key stakeholders.

### Data Structure

The dataset used was compiled from Car45.com (a vehicle marketplace in Nigeria). The structure includes the following:

Description, Amount (₦), State, City, Make, Model, Year Of Manufacturing, Color, Condition(Vehicles segmented into Brand New, Foreign Used, and Nigerian Used), Mileage(km), Engine Size
, Horse_power (hp), Body_Build, Fuel_type, Transmission.

### Data Analysis Process (Using Excel)

The analysis was carried out entirely in Microsoft Excel, from data preparation to visualization, before the results were modeled into the final dashboard. The steps are outlined below:

**1. Data Collection**

* Raw data was sourced from Car45.com, containing information on car prices, mileage, performance, brand, model, color, and transmission type.

* The dataset included both structured fields (numerical data like price, mileage, horsepower) and categorical fields (car brand, model, color, and transmission).

**2. Data Cleaning & Preparation**

* Removed duplicates and irrelevant columns.

* Standardized column headers for consistency.

* Handled missing values by either imputing with averages (for numerical fields) or excluding incomplete records (for categorical fields).

* Converted monetary values to a consistent format in ₦ (Nigerian Naira).

* Normalized mileage, horsepower, and engine size into comparable units.

**3. Data Transformation**

* Grouped car models into their respective brands.

* Categorized car conditions into Brand New, Foreign Used, and Nigerian Used.

* Created a consolidated list of the Top 10 car brands and colors.

* Added calculated fields to support analysis, such as:

    - Average Price per Brand

    - Mileage Bands (e.g., 0–10k km, 10k–50k km, etc.)

    - Transmission Split (Automatic vs. Manual)

**4. Exploratory Analysis (Excel Functions)**

Applied Pivot Tables to summarize data across key dimensions:

* Car model counts.

* Distribution of colors.

* Transmission preferences.

* Average KPIs (price, mileage, horsepower, engine size).

* Applied sorting and filtering to identify top-performing brands and features.

**5. Visualization (Excel Charts)**

* Created bar charts for Top 10 car brands and Color Preferences.

* Built a donut chart for Transmission Type preference.

* Designed KPI cards for Price, Mileage, Horsepower, and Engine Size using cell formatting.

* Inserted a map chart (using Excel’s geographic visualization feature) to display location spread across Nigeria.

**6. Dashboard Design**

* Combined all elements (KPIs, charts, and map) into a single interactive Excel dashboard.

* Used slicers and filters for car segmentation (Brand New, Foreign Used, Nigerian Used).

* Formatted the dashboard for readability (consistent fonts, icons, and a dark theme layout).

<img width="1220" height="595" alt="Screenshot 2025-08-20 212618" src="https://github.com/Femi-Valor/Nigeria-Car-Market/blob/main/Screenshot%202025-09-09%20170547.png" />
- <a href="https://github.com/Femi-Valor/Nigeria-Car-Market/blob/main/car.xlsx">live interaction


### Insights Deep Dive

**1. Market Averages (Pricing & Performance)**

Average Price: ₦5.0M

This suggests the Nigerian market is dominated by mid-range vehicles, making cars moderately affordable compared to global averages. However, for a country where income levels vary widely, foreign-used cars bridge the affordability gap.

Average Mileage: 28,000 km

Vehicles within this mileage range are relatively lightly used, which aligns with the preference for foreign-used (Tokunbo) imports that often enter Nigeria with moderate usage.

Average Horsepower (217 hp) & Engine Size (3.1L)

Indicates a market leaning towards high-performance and bigger engine cars rather than small, fuel-efficient vehicles. This reflects consumer taste for durability, roadworthiness on Nigerian terrain, and status symbols.

**2. Brand & Model Popularity**

Toyota is by far the market leader, consistently dominating across Nigerian cities. Its reputation for reliability, affordability, and strong resale value makes it the default choice for many buyers.

Honda ranks next, widely seen as Toyota’s closest competitor, appealing to middle-income earners.

Mercedes-Benz and Lexus are also popular, showing a significant demand for premium/luxury cars among upper-class buyers.

Lower market share brands such as Ford, Kia, Hyundai, and Volkswagen suggest niche adoption, either for specific car segments (SUVs, hatchbacks) or due to availability in the used-car import market.

Key Interpretation:

Car dealers can maximize returns by prioritizing Toyota and Honda for mass appeal while also stocking Mercedes-Benz and Lexus for higher-income buyers.

**3. Color Preferences**

Black, Gray, and Silver dominate the Nigerian car market. These neutral tones are perceived as:

Prestigious and stylish (black).

Low-maintenance in terms of dirt visibility (gray/silver).

Higher resale value, since these colors are universally accepted.

White cars also feature strongly, often chosen for corporate fleets and commercial use due to ease of branding and cost-effectiveness.

Bright colors (Red, Blue, Green, Gold) are much less common. This indicates that Nigerian buyers prefer neutral and classic tones over flashy colors, possibly due to cultural perceptions of elegance and resale considerations.


**4. Transmission Preferences**

A striking 94% of Nigerian drivers prefer automatic cars, compared to only 6% for manual cars.

This massive skew suggests:

Ease of driving is a top priority in congested urban environments.

Nigeria is aligning with global automotive trends, moving away from manual gearboxes.

Manuals may still hold a place in niche contexts (e.g., commercial transport, rural driving).


**5. Market Segmentation (Brand New vs. Used Cars)**

The Nigerian market remains dominated by foreign-used cars (Tokunbo) due to affordability compared to brand new cars.

Nigerian-used cars make up a moderate share, appealing to budget buyers.

Brand-new cars are the least represented due to their high cost, though demand exists in elite and corporate markets.

**6. Geographic Distribution**

Car demand is spread across urban centers, with Lagos, Abuja, and Port Harcourt being the biggest hubs.

This reinforces the trend that urbanization drives vehicle ownership, while rural areas remain underserved.

### Recommendations
**1. For Car Dealers & Importers**

Stock inventory strategically:

Focus heavily on Toyota and Honda for mass-market sales.

Include Mercedes-Benz and Lexus for the premium/luxury segment.

Align with color demand: Import and sell more black, gray, silver, and white cars, as these dominate buyer preference and resale value.

Transmission strategy: With 94% preference for automatic cars, stock predominantly automatic models. Keep manual cars only for niche buyers (e.g., commercial drivers, rural users).

Foreign-used focus: Since foreign-used (Tokunbo) cars dominate the market, build stronger partnerships with international exporters for steady supply.

Geographic targeting: Increase dealership presence and advertising in Lagos, Abuja, and Port Harcourt, which are the largest car hubs.

**2. For Policy Makers & Regulators**

Support affordable financing: Introduce vehicle loan schemes or flexible financing to make brand-new cars more accessible for middle-income Nigerians.

Encourage eco-friendly vehicles: Reduce tariffs on hybrid and electric vehicles (EVs) to promote sustainability in Nigeria’s car market.

Quality control: Enforce stricter import regulations to limit the inflow of unsafe or substandard foreign-used cars.

Infrastructure support: Invest in road quality and maintenance — larger engine sizes are partly a response to poor roads. Better infrastructure could gradually shift demand toward smaller, fuel-efficient cars.

**3. For Car Buyers**

Value for money: Toyota and Honda offer the best balance between cost, reliability, and resale value.

Think resale: Buyers should choose neutral colors (black, gray, silver, white) to maximize resale opportunities.

Mileage awareness: Even though most cars fall around 28,000 km, buyers should inspect carefully, as odometer fraud is common in used-car markets.

Automatic preference: Since automatic cars dominate, buyers should consider future maintenance costs and parts availability, which may be higher than manuals.

**4. For Auto Service & Ancillary Businesses**

Shift service capacity: With rising automatic car dominance, workshops should train more technicians in automatic transmission repairs.

Accessory market: Car accessory sellers should stock items for Toyota and Honda, as these have the broadest customer base.

Insurance providers: Insurers can develop packages tailored for foreign-used cars, which are the bulk of the market.

**5. For Future Research & Analytics**

Regional insights: Perform deeper analysis to understand regional differences (e.g., northern vs. southern states).

Trend monitoring: Track shifts in demand toward EVs and hybrids as global adoption increases.

Consumer behavior surveys: Combine data analysis with surveys/interviews to capture why Nigerians prefer certain brands, colors, and transmissions.

Longitudinal studies: Analyze changes in preferences over time to detect emerging market trends.

## Author
**[Olabamiji Michael Oluwafemi]** - Data Analyst 

