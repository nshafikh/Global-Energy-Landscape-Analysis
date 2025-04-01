# Global Energy Landscape Analysis
**(Check [project report](https://github.com/nshafikh/Global-Energy-Landscape-Analysis/blob/main/Project%20Report.pdf) for visualizations and in-depth analysis)**
![ezgif-592d071875027b](https://github.com/user-attachments/assets/e4ff814d-9593-4d46-ba6e-3c02cceba495)


## Project Overview

This project provides a comprehensive analysis of global energy consumption trends, electricity access, and the impact of income levels on energy use, with a focus on the evolving role of renewable and fossil energy sources across different regions and income brackets during a two-decade span.

## Data

- Primary Dataset: Sustainable Energy 2000-2020
- URL: https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy/data
- This dataset contains many useful factors, including sustainable energy indicators, across 176 countries from 2000 to 2020
- 1 table
- 21 columns
- 3520 rows (176 countries * 20 years)
- There are some columns (e.g., financial flows to developing countries) that have missing values. We will determine how to handle missing values upon further examination of the dataset.
- Additionally using World Bank dataset to identify population and age brackets for countries
- Income URL: https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups
- Population URL: https://data.worldbank.org/indicator/SP.POP.TOTL

## Key Insights:
- Total energy and electricity consumption is closely tied to income, with high income countries using the most and consumption decreasing across lower income brackets.
- While energy access influences energy usage, the disparity in consumption is much larger than the disparity in access.
- There is an inverse relationship between income level and reliance on renewable energy—low income countries source over 70% of their energy from renewables, while high income countries rely on them for less than 15% of their energy consumption.
- Nuclear energy is predominantly used by high income countries, which account for 85.8% of global nuclear electricity consumption. In contrast, lower income brackets use very little, making nuclear a much more significant part of the energy mix in wealthier nations.
- Fossil fuels remain the dominant electricity source worldwide.
- Global consumption of fossil fuels and renewable energy for electricity has generally increased gradually, while nuclear energy usage has remained stagnant.
- Latin America and the Caribbean have a strong reliance on renewable energy for electricity, while Western Europe depends heavily on nuclear energy, despite a decline in nuclear energy usage from 2000 to 2020.
- East Asia also relies significantly on nuclear energy but experienced a sharp decline in the early 2010s, with a recovery occurring towards the end of the decade.
- Financial inflows do not directly correlate with renewable energy initiatives, as other energy sources are growing at a faster rate.
- However, countries receiving financial inflows consistently experience an increase in overall renewable energy consumption, suggesting a possible correlation but not causation.
- High income countries were historically the largest CO₂ emitters but were recently surpassed by upper-middle income countries, largely due to China’s rapid emissions growth.
- China’s economic rise to upper-middle income status in 2010 coincided with a significant increase in its CO₂ emissions.
- Lower-middle income countries previously had similar emissions to upper-middle income countries, but the latter has since diverged due to rapid industrialization.
- Low income countries contribute the least CO₂ emissions and saw a noticeable drop in 2007, likely due to reclassification.
- Total emissions in high income countries have remained stable, but per capita emissions have declined, suggesting new entrants into the high income classification have lower emissions.
- Upper-middle income countries now dominate total emissions, reinforcing the link between industrial growth and CO₂ output.

