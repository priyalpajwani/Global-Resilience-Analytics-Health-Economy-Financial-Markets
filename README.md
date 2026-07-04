# Global-Resilience-Analytics-Health-Economy-Financial-Markets

## Overview:
The Covid-19 pandemic was initially a public health emergency, but its effects quickly extended beyond healthcare systems. Disruptions to healthcare services were followed by contractions in economic activity, labour market instability, changes in global trade patterns, and heightened volatility across financial markets. While these impacts are often examined independently, the pandemic demonstrated how closely connected healthcare, economic performance and financial stability can be.

This project analyses 15 World Bank indicators across seven global regions between 2018 and 2024 to examine how the pandemic reshaped health outcomes and how these effects propagated throughout the wider economy. Using Python and Tableau, 31 individual World Bank datasets were transformed, integrated and analysed to identify regional resilience, recovery patterns, and the relationships between healthcare, economic and financial systems. The insights were then generated for international policymakers and development organisations, including the World Bank, IMF, WHO and the United Nations.

## Research Focus:
The analysis is centred around the following question: How did COVID-19 reshape healthcare demand and what ripple effects did it have on the macroeconomy?

To address this question, the project examined three interconnected themes:

1. Healthcare and Social Outcomes:
   1.2 To what extent did infant mortality trends slow during COVID-19, and have regional disparities narrowed during recovery?
   1.3 Did stronger pre-pandemic immunisation systems and hospital bed capacity reduce disruptions to infant mortality and life expectancy?

4. Economic Performance:
- 2.1 How did GDP evolve before, during and after COVID-19?
2.2 How did inflation respond to the pandemic?
2.3 How did labour markets recover across regions?
2.4 Did tourism-dependent economies experience larger declines in exports and employment?

3. Financial Markets:
3.1 How did stock trading activity change before, during and after COVID-19?
3.2 How did market capitalisation evolve across regions?
3.3 Which regions experienced the strongest recovery in equity markets?
3.4 How did market capitalisation relate to inflation across regions?

## Data:
The analysis uses World Bank World Development Indicators (Open Data) covering the period from 2018 to 2024. A total of 31 raw datasets were collected and transformed into a single analytical dataset containing indicators across healthcare, economic and financial domains using Python in Jupyter Notebook.

Following this, fifteen indicators were selected for detailed analysis, including hospital beds per 1,000 people, infant mortality rate, life expectancy, immunisation coverage, birth rate, GDP, inflation, labour force participation, unemployment, employment in services, exports of goods and services, international tourism receipts, stocks traded, and market capitalisation.

The analysis focuses on seven World Bank regions: East Asia & Pacific, Europe & Central Asia, Latin America & Caribbean, Middle East, North Africa, Afghanistan & Pakistan, North America, South Asia, and Sub-Saharan Africa.

## Analytical Approach:
Built in Python (Pandas) and Tableau.

The original World Bank datasets were provided as individual CSV files, with countries represented as rows and years as columns. To prepare the data for analysis, each dataset was transformed using Python and Pandas, restructuring the data into a relational format before combining all indicators into a unified analytical dataset.

Following this, Exploratory Data Analysis (EDA) formed the core of the project, and interactive Tableau dashboards were developed across three analytical themes: healthcare, economy and financial markets to compare regional trends before COVID-19 (2018–2019), during COVID-19 (2020–2022), and the recovery period (2023–2024).

The analysis combined line charts, heatmaps, bubble charts, comparative tables and interactive dashboards to identify temporal trends, regional differences and relationships between indicators before translating these findings into policy recommendations.

## Tools & Technologies:

1. Programming & Analytics:
- Python (Pandas)
- Tableau
- Excel

2. Data & Analytics Techniques: 
- Data Wrangling & Transformation
- Exploratory Data Analysis (EDA)
- Data Integration
- Dashboard Development
- Data Visualisation

## Key Findings:
The findings suggest that healthcare resilience, economic performance and financial market stability were closely interconnected throughout the pandemic period rather than operating as separate systems.

1. Healthcare resilience varied considerably across regions, as countries with stronger pre-pandemic immunisation coverage and greater hospital bed capacity generally experienced smaller disruptions to infant mortality outcomes and demonstrated stronger recovery patterns.

2. Economic activity contracted sharply during 2020 across most regions before gradually recovering, however, the pace of recovery differed substantially. Regions with greater dependence on tourism, particularly MENAP, Latin America & Caribbean, and Sub-Saharan Africa, as well as service based industries, experienced larger disruptions to employment and exports, while inflation rose globally before peaking in 2022 and gradually stabilising thereafter.

3. It was also observed that financial markets followed a different trajectory from many underlying economic indicators. Stock trading activity increased significantly during the pandemic period before moderating during the recovery phase. East Asia & Pacific experienced the largest increase in stock trading activity during COVID-19, while North America recorded the strongest and most sustained growth in market capitalisation throughout the recovery period.

Taken together, these findings highlight the extent to which health outcomes, economic performance and financial market activity influence one another during periods of large-scale disruption.

## Why this matters:
The pandemic exposed how disruptions within healthcare systems can rapidly extend into labour markets, international trade and financial markets. Understanding these connections is important for policymakers, international institutions and organisations responsible for long-term resilience planning.

By bringing together health, economic and financial indicators within a single analytical framework, this project provides a broader perspective on regional recovery and highlights the importance of coordinated investment in healthcare capacity, economic diversification and financial resilience when preparing for future global shocks.

## Limitations:
1. Some World Bank indicators contain missing or provisional observations for the most recent years.
2. International tourism receipt data was only available up to 2020, limiting post-pandemic comparisons.
3. The analysis is exploratory in nature and identifies relationships rather than causal effects.
4. Regional aggregation provides a useful global perspective but may conceal substantial variation between individual countries.
5. The findings are dependent upon the quality, availability and consistency of publicly reported World Bank data.

## Note:
This project was developed as part of the Data Analytics and Visualisation for Business module at Imperial College London.
