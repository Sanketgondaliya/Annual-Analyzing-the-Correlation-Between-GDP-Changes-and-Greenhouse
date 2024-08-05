# Relationship between GDP Growth and Greenhouse Gas Emissions in India

## Abstract
This study explores the intricate relationship between annual Gross Domestic Product (GDP) variations and corresponding shifts in greenhouse gas (GHG) emissions. As societies strive for sustainable development, understanding the nexus between economic growth and environmental impact is crucial. Using a comprehensive dataset and advanced statistical models, our research reveals patterns, correlations, and potential causations between annual GDP changes and concurrent GHG emission alterations. The multi-dimensional approach considers diverse economic sectors, regional disparities, and technological influences. Findings illuminate the complex dynamics between economic prosperity and environmental consequences, offering practical insights for policymakers, businesses, and society. Recognizing nuanced connections between GDP dynamics and GHG emissions is vital for formulating effective strategies that promote sustainable development and address climate change challenges. This research contributes valuable insights to the discourse on sustainable growth and environmental preservation, guiding informed decision-making for a resilient and environmentally conscious future.

## Introduction
Climate change and environmental degradation pose significant challenges to India's sustainable economic development, impacting both financial and non-financial sectors (Haigh, 2011; Sullivan, 2014; Ozili, 2020). The potential consequences of climate change on the Indian economy are evident through climate risks, adversely affecting human well-being and livelihoods. Effectively managing these risks, addressing losses and damages, and making informed societal decisions become imperative, necessitating an understanding of the dynamics of future greenhouse gas emissions. Greenhouse gas emissions from India's industries play a crucial role in contributing to global climate change, presenting a critical challenge for the country.

India's economic growth, largely driven by industrialization and rapid urbanization, is intricately linked with increasing greenhouse gas emissions. As energy remains a pivotal catalyst for economic progress, the challenge lies in aligning developmental goals with environmental sustainability. The literature reveals divergent viewpoints on the relationship between economic growth and environmental pollution. Some argue that higher per capita income exacerbates environmental deterioration, while others contend that effective climate stress management is contingent upon economic growth, financial sector robustness, institutional efficacy, health sanitation systems, and educational levels.

In the Indian context, environmental concerns have become more pronounced, with economic growth often exerting pressure on natural resources. This project seeks to investigate the annual changes in Gross Domestic Product (GDP) and their association with greenhouse gas emissions, specifically focusing on India.

While existing studies have explored the global dynamics between economic growth and greenhouse gas emissions, limited attention has been directed toward the unique profile of India. The country's commitment to addressing climate change is evident through various initiatives, yet the challenge persists due to the energy demands of a growing economy. This study aims to fill this gap by scrutinizing the relationship between real GDP and greenhouse gas emissions in India.

Using panel data spanning from 2000 to 2017, our analysis reveals insights into the positive correlation between economic growth and greenhouse gas emissions in the Indian context. Higher income levels are found to drive increased demand for environmental protection, prompting the need for well-crafted environmental policies capable of mitigating emissions during periods of economic growth. This challenges the notion that economic growth alone can automatically reduce climate vulnerability in India; instead, the quality and sustainability of growth become crucial.

Methodologically, our approach integrates qualitative sequential methodology with empirical analysis and quantitative methods like Dynamic Ordinary Least Squares (DOLS), unit root tests, and cointegration techniques. This study contributes not only empirical evidence but also addresses specific gaps in the literature regarding the relationship between economic growth and greenhouse gas emissions in India. By providing nuanced insights into the implications of economic growth on India's greenhouse gas emissions, this research holds relevance for policymakers, academics, practitioners, and government bodies aiming to balance economic progress with environmental sustainability.

The subsequent sections of this paper will delve into the current discussions, present the sample and data, discuss the empirical results, and conclude with implications and avenues for future research specific to India.

## Datasets
- [Distribution of gross domestic product (GDP) across economic sectors from 2012 to 2022](https://www.statista.com/statistics/271329/distribution-of-gross-domestic-product-gdp-across-economic-sectors-in-india/)
- [Real GDP growth](https://ourworldindata.org/grapher/real-gdp-growth?tab=table)
- [Greenhouse gas emissions by sector](https://ourworldindata.org/grapher/ghg-emissions-by-sector-stacked?tab=table)
- [Total GHG emissions](https://ourworldindata.org/grapher/total-ghg-emissions?tab=table)
- [Annual change in GDP and CO₂ emissions](https://ourworldindata.org/grapher/co2-gdp-growth?tab=table&time=1961..2022)

## Articles
- [Global CO₂ emissions rebounded to their highest level in history in 2021](https://www.iea.org/news/global-co2-emissions-rebounded-to-their-highest-level-in-history-in-2021)
- [Frontiers in Environmental Science](https://www.frontiersin.org/articles/10.3389/fenvs.2022.934885/full)
- [Springer article on economic growth and emissions](https://link.springer.com/article/10.1007/s11356-022-23356-3)

## Methodology
### Greenhouse Gas Emissions Data
**Data Loading:**
- Load the greenhouse gas emissions dataset from the provided link.
- Inspect the structure of the dataset.

**Data Cleaning:**
- **Column Selection:** Select only the relevant columns needed for analysis (e.g., country, sector, year, greenhouse gas emissions).
- **Column Dropping:** Drop any unnecessary columns that do not contribute to the analysis.

**Exploratory Data Analysis (EDA):**
- Conduct exploratory data analysis to understand the distribution of greenhouse gas emissions across countries and sectors.
- Visualize key insights using charts or graphs.

### GDP Data
**Data Loading:**
- Load the GDP dataset from the provided link.
- Examine the structure of the dataset.

**Data Cleaning:**
- Filter the dataset to include only relevant countries for analysis.

**Exploratory Data Analysis (EDA):**
- Conduct exploratory data analysis on the GDP data for the selected countries.
- Visualize trends and patterns in GDP growth.

### Integration and Analysis
**Datasets:**
- Load the Annual change in GDP and CO₂ emissions dataset from the provided link.
- Examine the structure of the dataset.

**Correlation Analysis:**
- Explore the correlation between greenhouse gas emissions and GDP to understand the relationship.

**Time-Series Analysis:**
- Analyze the time-series relationship between GDP growth and greenhouse gas emissions.
- Identify any temporal patterns or trends.

## Objectives of the Study
- Analyze the distribution of gross domestic product (GDP) across economic sectors for India.
- Analyze the India GDP trend line (growth rate).
- Analyze greenhouse gas emissions by sector.
- Analyze annual greenhouse gas emissions for India.
- Analyze annual change in GDP and greenhouse gas emissions for India.

## Analysis of Datasets
1. **Year-wise Distribution of GDP by Sector:**
   - The pie chart shows that the distribution of GDP by sector is relatively even, with no one sector accounting for a majority of GDP. This is in contrast to many other countries, where the services sector tends to be much larger than the other sectors.
   - There are a number of possible explanations for this relatively even distribution of GDP in India. One possibility is that India's economy is still relatively underdeveloped, and as a result, there is a more even distribution of economic activity across different sectors. Another possibility is that India's government has made a conscious effort to promote balanced economic growth. Whatever the reason, the relatively even distribution of GDP by sector is a positive sign for India's economy. It suggests that the economy is not overly reliant on any one sector, and that it is therefore more resilient to shocks.
   - India's diverse economy results from historical roots, limited industrialization, a large rural population, and government policies. The informal sector adds to the services share. Recent trends show service sector growth, while policies like "Make in India" aim to boost manufacturing. Ensuring balanced, skill-driven, and sustainable growth is crucial for India's future development.

2. **India GDP Trend Line (Growth Rate):**
   - Government reforms: The Indian government has implemented a number of reforms in recent years, such as the Goods and Services Tax (GST) and demonetization. These reforms have had a mixed impact on the economy, with some sectors benefiting and others suffering.
   - Global factors: The Indian economy is also affected by global factors, such as the trade war between the United States and China. This trade war has led to a slowdown in global trade, which has hurt Indian exports.
   - Agricultural shocks: India is a largely agrarian economy, and agricultural output is often affected by weather shocks. For example, a drought in 2015 led to a decline in GDP growth.
   - Pandemic: The COVID-19 pandemic has had a major impact on the Indian economy, leading to a sharp decline in GDP growth in 2020.

3. **Greenhouse Gas Emissions by Sector:**
   - India's reliance on fossil fuels for electricity generation is the main reason behind the large share of emissions from the electricity and heat sector (35.3%). Coal is the primary source of fuel for power plants in India, and it is a major emitter of greenhouse gases.
   - Agriculture is another major source of emissions in India (23.4%). This is due to a number of factors, including the use of fertilizers, the burning of crop residues, and the raising of livestock.
   - Industrial processes such as cement production also contribute to India's greenhouse gas emissions (8.7%).
   - Other sectors, such as transportation, buildings, and waste, also emit greenhouse gases, but their contributions are smaller.

4. **Annual Greenhouse Gas Emissions for India:**
   - Coal reliance: India heavily relies on coal for electricity, a major emission source. Decarbonization efforts can cause drops, while

 increased coal use can cause rises.
   - Economic activity: Industrial activity and transportation, also emission sources, fluctuate with economic growth. Strong economic years can see emission increases.
   - Policy changes: Government policies like renewable energy targets or fuel regulations can influence emission trends.

5. **Annual Change in GDP and Greenhouse Gas Emissions for India:**
   - The chart shows the annual growth of GDP and greenhouse gas emissions in India from 2010 to 2022. It shows that GDP growth has been positive in all the years shown, while greenhouse gas emissions growth has been negative in all the years shown. This suggests that there is a negative correlation between GDP growth and greenhouse gas emissions growth in India.
   - Possible reasons for this negative correlation:
     - India's economy is becoming more service-oriented, and service industries tend to produce fewer greenhouse gases than manufacturing industries.
     - The Indian government is investing in renewable energy sources, such as solar and wind power.
     - India is becoming more energy efficient, due to factors such as improved building standards and the use of more efficient appliances.

## Limitations
- Missing dataset information about some years, GDP, and greenhouse gas emissions. As a result, we need to drop some values, which may affect the overall analysis.
- This analysis cannot definitively say that only the factors considered are affecting the GDP and greenhouse gas emissions. Other factors may also be influencing the annual change in GDP and greenhouse gas emissions trends.
- This analysis does not contain information on all countries in the world. Additionally, the data is acquired from different sources and merged, so human error is possible while creating the dataset.

## Conclusions
In summary, our study explored how India's economic growth is connected to the environment, specifically looking at changes in income and greenhouse gas emissions. We found that economic growth is linked to environmental impacts, influenced by history, society, and government decisions.

The research considered different aspects, such as where emissions come from and trends in the country's income growth. We discovered various factors at play - from the types of industries causing emissions to how the country's income changes each year. This information is crucial for decision-makers, like policymakers and businesses, to balance economic growth with environmental care.

While we gained valuable insights, there are some missing details and aspects we couldn't investigate. Future studies should fill these gaps and explore more factors. The main takeaway is that for India to continue growing well, it needs to strike a good balance between economic prosperity and environmental sustainability. This analysis does not prove the causal effect theory.

## References
✓ [MDPI](https://www.mdpi.com/2071-1050/6/6/3722)
✓ [investopedia](https://www.investopedia.com/articles/investing/121213/gdp-and-its-importance.asp)
✓ [sciencedirect](https://www.sciencedirect.com/science/article/pii/004727279401449X)

