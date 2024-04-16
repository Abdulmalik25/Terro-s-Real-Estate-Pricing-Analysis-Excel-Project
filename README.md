# Terro-s-Real-Estate-Pricing-Analysis-Excel-Project
Explore how environmental and social factors like crime rates, pollution levels, and educational resources impact property values in my latest project, "Terro’s Real Estate Pricing Analysis".Using regression models and exploratory data analysis in Excel, I uncover the key drivers that influence house pricing in diverse localities. Dive into my findings and methodologies on GitHub to see data-driven real estate insights in action!

## Objective
To analyse the real estate data to identify and quantify how various geographic and societal factors—such as crime rates, pollution levels, and proximity to educational resources—affect property values within specific localities. This analysis aims to provide Terro's Real Estate Agency with actionable insights to optimize property pricing strategies and enhance business.

## Data Description
| Attribute | Description                                                |
|-----------|------------------------------------------------------------|
| CRIME RATE| Per capita crime rate by town                              |
| INDUSTRY  | Proportion of non-retail business acres per town (in %)    |
| NOX       | Nitric oxides concentration (parts per 10 million)         |
| AVG_ROOM  | Average number of rooms per house                          |
| AGE       | Proportion of houses built prior to 1940 (in %)            |
| DISTANCE  | Distance from highway (in miles)                           |
| TAX       | Full-value property-tax rate per $10,000                   |
| PTRATIO   | Pupil-teacher ratio by town                                |
| LSTAT     | % lower status of the population                           |
| AVG_PRICE | Average value of houses in $1000's                         |

# Getting Started 
## Data Analysis
## Questions and Tasks

**1. Generate the summary statistics for each variable in the table. (Use Data analysis tool pack).**
   Some key findings:
   Crime Rate vs. Property Prices: Higher crime rates in an area are associated with lower property prices, reflecting safety's impact on real estate value.
   
   Industrial Presence and Tax Rates: Regions with a larger share of non-retail business acres experience higher property tax rates, highlighting the economic impact of industrial areas on local tax policies.
   
   Air Quality and Proximity to Work: Better air quality, indicated by lower nitric oxide levels, generally corresponds with closer proximity to employment centers, suggesting that less polluted areas might be more developed or desirable.
   <br>
   <img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/92ebcf2c-ec75-4b0c-95d9-c599b74cf7bb" alt="2a1" width="700" height="350"><img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/4084db07-d6b3-4058-bfd0-e58ab886c4b9" alt="2a2" width="550" height="350">

**2. Plot a histogram of the Avg_Price variable.**
   Skewness and Mean: The house prices show a right skew, with the median lower than the mean, indicating that a few high-value properties skew the average upwards.
   
   Standard Deviation: A standard deviation of 9.19 suggests a wide range of house prices, indicating significant diversity in property values.
   
   Histogram Analysis: The histogram presents a right-skewed distribution for house prices, pointing to the existence of higher-priced outliers.
   
   Positive Skewness: With a skewness of 1.108, the data confirms that more expensive houses disproportionately affect the price distribution.
   
   Kurtosis Insight: A kurtosis of 1.495 indicates a pleurokurtic distribution, meaning the data has a sharper peak than a normal distribution, emphasizing the presence of outliers.
   <br>
   <img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/b395da9d-51dc-44c7-82e9-32cb5e6f898a" alt="2b" width="550" height="350">

**3. Compute the covariance matrix.**
   Crime Rate vs. House Prices: There is a mild positive relationship between the crime rate and average house prices, suggesting higher crime areas might also have slightly higher house prices.
   
   Lower Status Population and Prices: There is a strong negative relationship between the percentage of lower status population (LSTAT) and house prices, indicating that areas with more lower-status residents tend to have lower property values.
   
   Property Tax and Education: Higher property taxes are associated with higher pupil-teacher ratios, which may reflect on the quality or demand for education in those areas.
   
   Room Count and Property Value: A positive relationship exists between the number of rooms in a house and its price, showing that larger houses typically command higher prices.
   
   Non-Retail Business and Property Age: Areas with more non-retail business space tend to have older properties, indicating a link between commercial land use and the age of residential buildings.
   <br>
   <img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/4ef7bdb1-77fb-499d-aa48-d2d531314f98" alt="2c" width="700" height="350">

**4. Create a correlation matrix of all the variables**
   a) Which are the top 3 positively correlated pairs and
   b) Which are the top 3 negatively correlated pairs.

   - **AVG_PRICE and LSTAT** exhibit a negative correlation, suggesting that a decrease in one variable is associated with an increase in the other.
   - The lower number of rooms in properties for people with higher LSTAT values can be attributed to the lower AVG_PRICE of houses in such areas.
   - **TAX and the distance of homes from the office** are positively correlated, indicating that people living in houses farther from the office tend to pay higher taxes.

   <br>
   <img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/0969bad5-820d-4920-8674-96446ed38d7c" alt="2d" width="700" height="350">

**5. Build your Model.**
   
   <br>
   <img src="https://github.com/Abdulmalik25/Terro-s-Real-Estate-Pricing-Analysis-Excel-Project/assets/153974173/f63a3b5f-98e3-46f8-b853-53b56617d95a" alt="2e" width="700" height="350">





