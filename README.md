# Suicide-Rates-Overview-1985-to-2016
1
1.1 Executive Summary
This project explores suicide rates from 1985 to 2016, aiming to provide valuable insights for 
policymakers, public health professionals, mental health experts, researchers, and the general 
public. Through rigorous analysis and data visualization, the project sheds light on the factors 
contributing to suicide rates. It identifies patterns and correlations among key variables such as 
population, GDP per capita, age, and gender. The analysis reveals that various factors, including 
population size, economic conditions, and socio-demographic characteristics influence suicide 
rates. The findings emphasize the importance of mental health support, evidence-based prevention 
strategies, socio-economic improvements, enhanced data collection, and international 
collaboration in addressing the complex issue of suicide. By implementing the recommendations 
outlined in this report, stakeholders can work together to develop effective strategies, policies, and 
interventions to combat suicide rates. By prioritizing mental health, addressing socio-economic 
disparities, and fostering collaboration, we can create a safer and healthier future for all, promoting 
awareness and informed decision-making to combat suicide rates effectively.
1.2 Introduction
Suicide is a pressing public health issue that demands our attention and understanding. In this 
project, we explore suicide rates from 1985 to 2016, aiming to shed light on the factors that 
contribute to this global concern. By delving into a comprehensive dataset, we seek to uncover 
patterns and correlations that can provide valuable insights for policymakers, public health 
professionals, mental health experts, researchers, and the general public. Through rigorous analysis 
and data visualization, we aim to make this complex topic more accessible, fostering awareness 
and informing evidence-based strategies to combat suicide rates. Join us on this journey as we 
uncover the multifaceted aspects of suicide and strive to create a safer and healthier future for all. 
Firstly, we will perform an exploratory analysis to gain a deeper understanding of the data, 
uncovering patterns, trends, and potential relationships between variables. This will enable us to 
identify key metrics within the dataset and establish relevant Key Performance Indicators (KPIs) 
that align with our objectives. To ensure the reliability and accuracy of our findings, we will 
diligently clean, filter, and edit the data according to our specific requirements, addressing any 
inconsistencies or outliers that may impact the analysis. Additionally, we will prioritize data 
quality and validity by thoroughly examining the dataset for errors, redundancies, and missing 
2
information. In cases where data is missing, we will employ appropriate imputation techniques 
such as linear regression, mean imputation, or ratio imputation to estimate the missing values. By 
implementing these steps, we aim to ensure the integrity of our analysis, paving the way for robust 
insights and informed decision-making.
1.3 Methodology 
The dataset used for this analysis is "Suicide Rates Overview from 1985 to 2016", obtained from 
Kaggle. 
Preprocessing Steps: 
Before the analysis, some preprocessing steps were taken to ensure data quality and consistency. 
The following steps were performed: 
1. Data Cleaning: A thorough examination of the dataset was conducted to identify and address 
missing values, inconsistencies, and outliers. 
2. Data Transformation: The dataset underwent a comprehensive assessment to determine if any 
transformation techniques were required. This assessment aimed to enhance the suitability of the 
data for subsequent analysis. 
3. Data Integration: The possibility of integrating multiple datasets to construct a unified dataset 
for analysis was explored. This integration process involved matching and merging variables based 
on common identifiers, such as country and year, to create a comprehensive dataset. 
Variables: The dataset includes the following variables: 
1. Country: The name of the country. 
2. Year: The year of the recorded data. 
3. Sex: The gender of the individual (male or female). 
4. Age: The age group of the individual (e.g., 15-24 years). 
5. Suicides_no: The number of suicides reported for the specific group. 
6. Population: The population counts for the specific group. 
7. Suicides/100k pop: The suicide rate per 100,000 population for the specific group. 
8. Country-year: A combination of country and year for convenience. 
9. HDI for year: The Human Development Index (HDI) for the specific year (if available). 
10. GDP_for_year: The GDP of the country for a specific year. 
3
11. GDP_per_capita: The GDP per capita of the country for the specific year. 
12. Generation: The generational cohort of the individual (e.g., Generation X, Boomers, Silent).
1.4 Data Analysis
Here are some insights that were obtained from the Descriptive analysis of the dataset:
1. Suicides: The dataset contains information on suicide counts (suicides_no). The minimum 
number of suicides recorded is 0, while the maximum is 22,338. The average number of suicides 
is approximately 242, and the median (50th percentile) is 25. The standard deviation is relatively 
high at 902, indicating significant variability in suicide counts across the dataset.
2. Population: The dataset includes population data, representing each observation's population 
(population) size. The minimum population recorded is 278, while the maximum is 43,805,210. 
The average population is approximately 1,844,794, with a median value of 430,150. The standard 
deviation suggests substantial variation in population sizes among the recorded data points.
3. Suicide Rate: The dataset provides information on the suicide rate per 100,000 population 
(suicides/100k pop). The minimum recorded rate is 0, indicating instances where no suicides 
occurred within a given population. The maximum rate is 224.97, reflecting a high concentration 
of suicides within a specific population. The average suicide rate is approximately 12.82 per 
100,000 population, with a median rate of 5.99. The standard deviation of 18.96 highlights notable 
disparities in suicide rates across different observations.
4. Human Development Index (HDI): The dataset incorporates the Human Development Index 
(HDI for year), which measures a country's overall development based on life expectancy, 
education, and income. The HDI values range from 0.483 to 0.944, with an average HDI of 0.7766. 
The distribution of HDI values indicates variations in development levels among the countries 
represented in the dataset.
5. GDP per Capita: The dataset includes information on the Gross Domestic Product (GDP) per 
capita. The minimum recorded value is USD 251, while the maximum is USD 126,352. The 
4
average GDP per capita is approximately USD 16,866, with a median value of USD 9,372. The 
standard deviation of USD 18,887 indicates significant disparities in economic prosperity across 
the dataset. 
These insights provide an overview of the key variables in the dataset and their basic statistical 
properties, offering a foundation for further analysis and investigation of relationships between the 
variables.
Here are some insights that can be derived from the non-numerical key performance variables in 
the dataset:
1. Country: The dataset includes information on the countries represented in the data. There are a 
total of 101 unique countries in the dataset. The country with the highest frequency in the dataset 
is Mauritius, appearing 382 times.
2. Sex: The dataset includes gender information, categorized as male and female. The variable 'sex' 
has two unique categories. The most frequent category is male, appearing 13,910 times in the 
dataset.
3. Age: The dataset provides age groups for the observations. The 'age' variable has six unique 
categories representing different age ranges. The age group "15-24 years" has the highest 
frequency, appearing 4,642 times in the dataset.
4. Country-Year: The dataset includes country and year information. The 'country-year' variable 
has 2,321 unique combinations, indicating multiple observations for each country in different 
years. The combination "Albania1987" appears 12 times, the highest frequency among the 
country-year combinations.
5. GDP for Year: The dataset includes each year’s Gross Domestic Product (GDP). The 
'gdp_for_year' variable has 2,321 unique values, representing different GDP values for different 
years. The highest frequency is 12, indicating that 12 observations share the same GDP value.
5
6. Generation: The data set includes information about the generation to which individuals belong. 
The 'generation' variable has six unique categories representing different generations. The most 
frequent generation in the dataset is Generation X, appearing 6,408 times. These insights provide 
an overview of the dataset's non-numerical variables, unique categories, and frequency 
distribution. Understanding these variables can help in further analysis, such as exploring patterns 
and relationships based on country, gender, age, country-year combinations, GDP, and generation.
Correlation Heatmap: The Correlation Heatmap below reveals a major insight we observed a 
positive correlation of 0.616 between the number of suicides and the population. This indicates 
that as the population increases, the number of suicides also tends to increase. 
Top 10 Countries with Highest Suicide Rate: The Country and Suicide number bar plot illustrates 
that the Russian Federation has the largest overall number of suicides throughout time. In contrast,
the United Kingdom has the lowest.
6
Total Suicide by Age group: The age and suicide rate bar plot illustrate that those aged 35 to 54 
years perpetrated the most suicides over time, while people aged 5 to 14 years had the fewest 
suicide events.
Total Suicides by Sex: It has been discovered that more males have committed suicide across all 
countries throughout time.
7
Total Suicides by Generation: It is observed that the Boomers Generation had more suicide 
occurrences, while Generation Z had the least.
Total Suicides by Year: It is observed that the year with the highest number of suicides is 1999 
and the year with the lowest number of suicides is 2016.
8
Interpretation of Skewness of Dataset:
Suicides_no: Skewness = 10.352910 The distribution of the "suicides_no" column is positively 
skewed (tail on the right side) as the skewness value is significantly greater than 0. This indicates 
a few years with many suicides, resulting in a long right tail.
Population: Skewness = 4.459414 The distribution of the "population" column is positively 
skewed (tail on the right side) as the skewness value is greater than 0. This suggests there are 
relatively few years with very large populations, resulting in a long right tail.
Suicides/100k pop: Skewness = 2.963414 The distribution of the "suicides/100k pop" column is 
positively skewed (tail on the right side) as the skewness value is greater than 0. This indicates a
relatively few years with a high suicide rate per 100k population, resulting in a long right tail.
In summary, most of the columns in the dataset exhibit positive skewness, indicating that the tail 
of the distribution is longer on the right side. This means there are relatively few extreme values 
in the positive direction, which might correspond to years with higher suicides, larger populations, 
or higher suicide rates.
9
Interpretation of Kurtosis:
Suicides_no: Kurtosis = 157.168842 The kurtosis value for the "suicides_no" column indicates 
that the distribution has heavy tails and a sharper peak compared to a normal distribution. This 
suggests the presence of extreme values and a significant deviation from normality.
Population: Kurtosis = 27.407176 The kurtosis value for the "population" column indicates that 
the distribution has heavy tails and a sharper peak compared to a normal distribution. This suggests 
the presence of extreme values and a significant deviation from normality.
Suicides/100k pop: Kurtosis = 12.165745 The kurtosis value for the "suicides/100k pop" column 
indicates that the distribution has heavy tails and a sharper peak compared to a
normal distribution. This suggests the presence of extreme values and a significant deviation from 
normality.
In summary, most of the columns in the dataset exhibit high positive kurtosis, indicating heavytailed distributions with a sharper peak compared to a normal distribution. This suggests
the presence of extreme values and a significant departure from normality, implying that the 
distributions are leptokurtic.
1.5 Recommendations
Improve mental health support: Given the complex nature of suicide rates, it is crucial to prioritize 
mental health support and resources. Governments and healthcare organizations should allocate 
adequate funding and develop comprehensive strategies to provide accessible and affordable 
mental health services. This includes promoting awareness, early intervention, and destigmatizing 
mental health issues to encourage individuals to seek help.
Implement evidence-based prevention strategies: Policymakers and public health professionals 
should implement strategies tailored to different demographics, age groups, and risk factors 
identified in the analysis. These strategies may include educational programs, community outreach 
initiatives, and targeted interventions to address different populations' specific needs and 
vulnerabilities.
10
Enhance data collection and reporting: To improve the understanding of suicide rates, it is crucial 
to enhance data collection efforts. Governments should invest in comprehensive and standardized 
data collection systems to ensure accurate and consistent reporting of suicide cases. This includes 
collecting data on important variables such as mental health history, access to means, and 
underlying causes to identify patterns and risk factors more effectively.
Foster international collaboration: Suicide is a global issue that requires collaboration among 
countries. International organizations, governments, and NGOs should collaborate to share best 
practices, research findings, and resources. This collaboration can lead to a more comprehensive 
understanding of suicide rates and development of effective prevention strategies across borders.
1.6 Conclusion
By analyzing the KPIs we can conclude that suicide is a complex public health issue influenced 
by various factors. This analysis has shed light on the relationship between suicide rates and 
variables such as population, human development, GDP per capita, age, and gender. While the 
analysis provides valuable insights, it is important to recognize that suicide is a multifaceted 
problem that requires a comprehensive approach. To effectively address suicide rates, it is essential 
to prioritize mental health support, implement evidence-based prevention strategies, address socioeconomic disparities, enhance data collection efforts, and foster international collaboration. By 
taking a holistic approach and investing in these recommendations, policymakers, public health 
professionals, and communities can work together to create a safer and healthier future for 
individuals worldwide.
