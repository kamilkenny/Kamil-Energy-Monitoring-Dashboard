
# UK ELECTRICITY GENERATION & DECARBONISATION POWER BI ANALYTIC DASHBOARD (2020-2025 GENERATION MIX)
![NESO (3)_page-0001](https://github.com/user-attachments/assets/5eccd993-8d11-4d53-9741-8fa3c726dbc9)
An analytical dashboard developed in Microsoft Power BI to explore Great Britain’s electricity generation mix over the period 2020–2025 using half-hourly system data. The objective of the study was to construct an interactive visual framework capable of examining structural fuel composition, renewable penetration levels, carbon intensity behaviour, and system stress indicators at a national scale. The dashboard was designed not merely as a visualisation exercise, but as a structured analytical tool aligned with large-scale energy system objectives such as decarbonisation monitoring, operational flexibility assessment, and generation planning insight.

The design sought to determine how the GB electricity mix is structured during the study period, whether renewable generation has materially displaced fossil fuels, how fuel composition influences carbon intensity, and when the system experiences elevated stress or emissions.

# Data Context and Structure

The dataset consisted of half-hourly generation records across major fuel sources including gas, coal, nuclear, wind, solar, hydro, biomass and imports. Aggregated system metrics such as total generation, fossil contribution, renewable contribution, zero-carbon generation, low-carbon generation and carbon intensity were also included. The availability of both absolute generation values in megawatts and percentage shares enabled analysis of structural composition independent of demand fluctuations.

The data was transformed within Power Query to ensure appropriate data types, temporal segmentation and structural reorganisation for visual modelling. DAX measures were developed to support derived metrics such as net demand and carbon composition breakdown.
<img width="1466" height="830" alt="2024 B" src="https://github.com/user-attachments/assets/43f5ac49-0e2a-4bd2-ac2c-98a1d83d7c4f" />


The dashboard begins with a high-level KPI panel presenting total generation, average carbon intensity, average renewable share, peak demand, and record generation values for wind and solar. This section provides an immediate executive snapshot of system performance during the study period. It allows rapid evaluation of overall demand magnitude, renewable penetration levels and emission intensity trends.

By consolidating key indicators at the top of the dashboard, the design mirrors the reporting style used within transmission system operations and policy briefings, ensuring clarity and immediate interpretability.
# Executive-Level System Indicators
The dashboard begins with a high-level KPI panel presenting total generation, average carbon intensity, average renewable share, peak demand, and record generation values for wind and solar.
# Structural Fuel Mix Analysis 
The structural behaviour of the generation mix was examined through stacked area charts representing both absolute megawatt contribution and percentage share composition.
# Fossil versus Renewable Transition
A dual-line visual comparing fossil share and renewable share was constructed to assess structural crossover behaviour. This comparison highlights the relative balance between dispatchable fossil generation and variable renewable output. This comparison directly supports evaluation of national transition goals by illustrating how renewable penetration is reshaping the structural composition of the generation mix.
# Carbon Intensity Behaviour and Correlation
Carbon intensity trends were analysed using temporal line charts and correlation-based scatter plots. The trend visual reveals seasonal variation, with winter periods displaying elevated carbon intensity consistent with increased reliance on fossil-based generation during high-demand conditions.

![NESO (3)_page-0002](https://github.com/user-attachments/assets/e41e0645-30fd-4a58-8cd9-885b28585b90)

# Net Demand and System Stress Indicators
Net demand was calculated as total generation minus wind and solar output, representing the demand that must be met by dispatchable sources such as gas, nuclear and imports. This derived metric provides insight into system stress and flexibility requirements.
# Zero Carbon versus Low Carbon Decomposition
A waterfall visual was developed to distinguish between zero-carbon generation and low-carbon generation. Zero-carbon output, comprising wind, solar, hydro and nuclear, was separated from biomass to illustrate the structural composition of low-carbon supply. This decomposition clarifies that low-carbon generation is not entirely zero-emission, and it quantifies the specific contribution of biomass within the overall low-carbon category.
# Temporal Behaviour Heatmap
A matrix-based heatmap was constructed to visualise hourly demand behaviour across months. Conditional formatting was applied to reveal seasonal and intraday patterns.

# Strategic Relevance 
The 2020–2025 exploratory analysis successfully delivered a structured and insight-driven Power BI dashboard capable of visualising generation dynamics, quantifying renewable displacement of fossil fuels, demonstrating carbon-emission relationships, and identifying operational stress periods.
The dashboard is suitable for executive reporting, energy system analysis, policy discussion and portfolio demonstration. Its modular design allows for scalability and future expansion into longer historical datasets or forecasting extensions.



































# Kamil-Energy-Monitoring-Dashboard using Power BI
# Residential Energy Monitoring Dashboard (Power BI)


This Power BI dashboard was developed to track and analyze power consumption in a residential building at the appliance level (light bulbs). The visualization highlights daily, weekly, and monthly electricity usage patterns, enabling better understanding of consumption behavior and identification of high-use periods.

This Power BI dashboard was developed to track and analyze power consumption in a residential building at the appliance level (light bulbs). The visualization highlights daily, weekly, and monthly electricity usage patterns, enabling better understanding of consumption behavior and identification of high-use periods.

Key Features:

Real-time monitoring of electricity consumption by light bulbs.

Trend analysis of usage patterns across different time scales.

Interactive filters for exploring specific rooms or time intervals.

Clear visual indicators (KPIs, charts, and graphs) to support energy efficiency awareness.

This project demonstrates how data visualization can simplify energy monitoring in residential settings and support efforts to reduce unnecessary electricity consumption.

![energy dashboard 2](https://github.com/user-attachments/assets/ada4d2f2-153b-41a5-a4ed-0bdd8528e392)

