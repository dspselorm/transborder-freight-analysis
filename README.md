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
1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Modeling/Analysis**
5. **Evaluation**
6. **Deployment (Presentation & Reporting)**
