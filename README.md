## TransBorder Freight Data Analysis
This project is part of the Azubi Africa Talent Mobility Program. The goal is to analyze freight data from the U.S. Bureau of Transportation Statistics (BTS) to uncover insights related to efficiency, safety, and environmental impact across different modes of transportation (road, rail, air, and water).

### Project Objectives
1. **Uncover Freight Movement Patterns** - Analyze the movement of freight across different transportation modes, and identify trends in volume, routing, and modes of transportation used across regions and periods.
2. **Identify Operational Inefficiencies** - Investigate areas where transportation systems may experience inefficiencies, such as congestion points, delays, or underutilized infrastructure, and propose methods to optimize resource use and improve throughput.
3. **Analyze Environmental Impact** - Assess the environmental impact of freight transportation by studying data on emissions, fuel usage, and sustainability metrics across different modes of transportation, and recommend strategies for reducing the carbon footprint of the sector.
4. **Safety and Risk Assessment** - Identify transportation safety incidents related to freight, evaluate their causes and consequences, and suggest  recommendations for improving safety protocols.
5. **Analyze how Economic Disruptions** (e.g., trade patterns, policy changes, or global events) impact freight movements and overall transportation efficiency.
6. **Provide Data-Driven Recommendations** - Based on the analysis, provide actionable recommendations to enhance the performance, sustainability, and safety of the transportation systems that handle cross-border freight.

### Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning, analysis, visualization
- **Jupyter Notebook** – Iterative analysis (via Google Colab)
- **GitHub** – Version control and project documentation

### Dataset Description
The dataset spans from **January 2020 to September 2024** and is sourced from the U.S. Bureau of Transportation Statistics (BTS). It contains monthly transborder freight data between the U.S., Canada, and Mexico.

### Key Columns
- **YEAR & MONTH** - Time of record
- **COUNTRY & STATES** - Country and sub-national region involved in freight movement
- **COMMODITY2** - Type of commodity traded (e.g., Meat, Machinery, Vehicles)
- **DISAGMOT** - Mode of transport used (Truck, Rail, Air, Vessel, etc.)
- **VALUE** - Value of goods (in USD)
- **SHIPWT** - Shipment weight (in KG)
- **FREIGHT_CHARGES** - Shipping cost
- **TRDTYPE** - Type of trade – Export or Import
- **DEPE** - Entry/exit port or district

### CRISP-DM Steps
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Analysis & Evaluation
5. Presentation & Reporting


### Key Questions Addressed
1. Which transport modes dominate cross-border trade?
2. How have freight trends evolved across Canada and Mexico?
3. What are the top commodities by value and weight?
4. Which ports handle the most freight?
5. How do trade volumes vary seasonally and annually?
6. Are containerized or non-containerized shipments more valuable?
7. How do freight charges correlate with trade value?

### Data Preparation
1. Handled over 35M rows, reduced to ~28M after cleaning.
2. Filled missing values using logical groupings and inferred patterns (e.g., mode, location).
3. Standardized categorical values and converted timestamps for trend analysis.
4. Replaced or retained critical nulls in columns like MEXSTATE, CANPROV, and DEPE.

### Key Insights
1. Truck transport (Mode 5) remains the backbone of freight by both value and weight.
2. Canada leads Mexico in exports, though both show similar seasonal patterns.
3. Machinery (Commodity 84) and Fuel (Commodity 27) dominate in both value and weight.
4. Laredo, TX (Port 2304) handles nearly 4x more trade value than any other port.
5. Trade peaks occur in Q1 each year, driven by restocking and fiscal schedules.
6. Non-containerized shipments carry higher average value, likely for specialized goods.
7. Freight charges correlate strongly with trade value—especially in modes like Pipelines and Rail.

### Recommendations
1. Improve Mexico import reporting for balanced analytics.
2. Invest in top trade hubs (e.g., Laredo, Detroit) to boost logistics capacity.
3. Optimize transport mode selection to mitigate cost spikes.
4. Plan around Q1 surges to avoid seasonal congestion.
5. Account for outliers in pricing models to avoid distortions.
6. Enhance freight handling for bulky cargo, especially for non-containerized shipments.
