# Data-Science-and-AI---Group-3

## I.	Introduction / Problem Statement
In the intricate web of the Philippine socio-economic landscape, the persistent challenge of poverty poses an obstacle, hindering the nation's path to comprehensive development. Despite commendable economic growth, poverty endures, characterized by low income, constrained employment opportunities, and limited access to essential services. 

Aligning itself with the global commitment encapsulated in the Sustainable Development Goal (SDGs), the Philippines underscores its dedication to fostering a more equitable society. Embracing the principles of SDG 1: "No Poverty," the nation recognizes the importance of eradicating all facets of poverty, ensuring that every individual has equal access to the essentials necessary for a dignified life.

In the fabric of a nation's economic landscape, one of the pivotal contributors is the rural economy, wielding both the potential for prosperity and the challenges of poverty. Rooted in the vast expanses beyond urban centers, the rural economy encompasses a diverse range of agricultural activities, non-farm enterprises, and local industries. Its significance extends far beyond the idyllic scenes of farmland, encompassing the livelihoods of a substantial portion of the population.
  
For the Philippines, rural economies is considered as the backbone of the agricultural sector, nurturing the cultivation of crops and the rearing of livestock that form the bedrock of food security. Beyond agriculture, these economies host a spectrum of non-farm activities, from small-scale enterprises to traditional crafts, creating a web of interconnected economic activities that sustains communities.

However, while the rural economy is a wellspring of economic contributions, it also grapples with the shadows of poverty. The challenges are manifold, encompassing factors such as limited access to resources, market fluctuations, and vulnerability to climate change. As a result, a significant proportion of the rural populace contends with lower income levels, constrained employment opportunities, and disparities in access to essential services. In relation to this, understanding the dynamics of the rural economy as a contributor to both economic growth and poverty is essential for crafting effective policies.

Income disparities in the rural economy serve as a testament to the pervasive hold of poverty, as a significant portion of the population remains below the national poverty line. Limited stable employment opportunities increase vulnerability, exposing individuals and families to a state of socio-economic instability. With these, a more in-depth analysis of these indicators, including rural income, agricultural wages, non-farm income, and employment, will be undertaken to glean a comprehensive understanding of the factors contributing to the issue of poverty for targeted and effective interventions to address the root causes and foster inclusive progress.

## II.	Gathered Data / Dataset 
The dataset employed in this project is a comprehensive compilation of economic and agricultural indicators, providing a detailed snapshot of the socio-economic insight across various regions in the Philippines. These indicators encompass a wide array of quantitative measures that capture the dimensions of economic and agricultural activities, shedding light on the characteristics and disparities that exist among different geographic areas within the country.

Titled "A Few Poverty Indicators for the Philippines by Region," the dataset has been sourced from Kaggle.com, with the last recorded update dating back to the year 2018. Kaggle is a renowned platform that hosts datasets and facilitates collaborative data science projects. This particular dataset serves as a valuable resource for understanding poverty dynamics in the Philippines, providing insights into various indicators across different regions of the country.

Within this dataset, economic indicators encompass a range of variables such as income, wages, and employment. These indicators serve as crucial metrics for assessing the financial health and productivity of each region. This regional approach acknowledges the diversity within the Philippines, recognizing that economic and agricultural dynamics can vary significantly from one region to another due to factors. Presented below are the description of the columns in the dataset:

1.	regDesc: Region description, indicating the name of each region in the dataset.
2.	agr_wage_farm_workers_allgender_2015: Average agricultural wage for farm workers of all genders in 2015.
3.	agr_wage_farm_workers_male_2015: Average agricultural wage for male farm workers in 2015.
4.	agr_wage_farm_workers_female_2015: Average agricultural wage for female farm workers in 2015.
5.	avg_annual_total_incm_farm_households_02_03: Average annual total income for farm households in 2002-2003.
6.	avg_annual_farm_incm_farm_households_02_03: Average annual farm income for farm households in 2002-2003.
7.	avg_annual_off_farm_incm_farm_households_02_03: Average annual off-farm income for farm households in 2002-2003.
8.	avg_annual_non_farm_incm_farm_households_02_03: Average annual non-farm income for farm households in 2002-2003.
9.	avg_annual_other_sources_incm_farm_households_02_03: Average annual income from other sources for farm households in 2002-2003.
10.	avg_rural_income_2000: Average rural income in the year 2000.
11.	total_emply_2016: Total employment in the year 2016.
    
The dataset is a small-sized tabular dataset, having 11 columns and 17 rows, wherein the types of variables include both numerical values in decimals (e.g., average wages, income figures) and categorical values in strings (e.g., region descriptions). The provided dataset has 11 columns to represent information for different regions in the Philippines. The row of the dataset corresponds to each of the regions in the country excluding National Capital Region; hence, giving a total of 16 rows. These include Autonomous Region in Muslim Mindanao (ARMM), Bicol Region, Cagayan Valley, CALABARZON, Cordillera Administrative Region (CAR), Caraga, Central Luzon, Central Visayas, Davao Region, Eastern Visayas, Ilocos Region, MIMAROPA, Northern Mindanao, SOCCSKSARGEN, Western Visayas, and Zamboanga Peninsula. Presented in Figure 4 is the descriptive statistics of the dataset which include the characteristics per category, such as number of not-empty values, mean, standard deviation, minimum value, and maximum value.

[Link of the Dataset](https://www.kaggle.com/datasets/statchaitya/a-few-poverty-indicators-for-philippines-by-region/data )


## III.	Objectives
The primary objective of the study is to conduct a comprehensive analysis of the dataset containing key poverty indicators for the Philippines by region, leveraging data science methodologies, with the aim of having an overview of the status of poverty in each region. Specifically, this study aims to:
1.	Explore and preprocess the dataset focusing on variables related to agricultural wages, average incomes, and total employment to ensure data integrity and completeness;
2.	Conduct correlation analyses to identify relationships between variables, specifically the following:

  	  2.1. Agricultural wage rates and farm income

  	  2.2. Non-farm income and rural income

      2.3. Total employment and total income
  	
4. 	Implement a linear regression model to analyze the relationships between the selected and specified variables and evaluate the model's ability to predict the linearity of these variables and assess their respective impacts on overall income for farm households;
5. 	Employ a Decision Tree Model to classify instances based on the selected variables to reveal categorical relationships and key influencing factors and evaluate the model’s performance for a comprehensive understanding of farm households' income dynamics; and
6.	Conduct a comparative analysis between the linear regression model and the Decision Tree Model in terms of their effectiveness in analyzing the relationships among variables to identify the strengths and limitations of each model for a more robust interpretation of farm households' income dynamics.


