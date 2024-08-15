Data Collection, Cleanup, and Exploration
Data Source and Selection
We utilized NASA's sea level datasets for our analysis, chosen for their accuracy and extensive global coverage. The data spans from late 1992 to early 2024, collected via satellite, which provides high-resolution measurements crucial for tracking sea level changes over time.
Data Collection Process
* Source: NASA's sea level dataset
* Coverage: Global sea level measurements
* Time Period: Late 1992 to early 2024
* Format: Initially in CSV and NetCDF formats
Data Exploration and Cleanup
1. Exploration:
    * Initial Review: Analyzed the dataset's structure and content to understand its scope and quality.
    * Descriptive Statistics: Calculated summary statistics to grasp the data's distribution and central tendencies.
    * Visualization: Created initial plots to visualize global sea level trends and identify any apparent patterns or anomalies.
2. Cleanup:
    * Handling Missing Values: Imputed or interpolated missing data points based on surrounding values or using statistical methods.
    * Correcting Anomalies: Identified and corrected outliers or inconsistencies that could skew results.
    * Data Formatting: Converted data into a consistent time-series format, aggregated regional data for specific seas, and standardized units for analysis.
Approach to Achieving Project Goals
Analytical Approach
1. Exploratory Data Analysis (EDA): Conducted to understand data characteristics and identify initial trends.
2. Trend Analysis: Used statistical methods to quantify sea level rise trends, including linear regression and moving averages.
3. Visualization: Created various plots, such as time series graphs and trend lines, to illustrate sea level changes.
4. Forecasting: Applied predictive modeling techniques (e.g., Prophet) to estimate future sea level changes based on historical data.
Unanticipated Insights and Problems
* Data Gaps: Some regions had sparse data, which complicated regional analysis. We addressed this by using interpolation and focusing on regions with more complete datasets.
* Model Variability: Forecasting models showed variability due to uncertainties in emission scenarios and ice sheet dynamics. We handled this by running multiple scenarios and providing a range of projections.
Results and Conclusions
Key Findings
* Trend Identification: Observed significant upward trends in sea levels across selected seas.
* Regional Variations: Noted differences in the rate of sea level rise between regions. For instance, the Mediterranean Sea experienced a slower rise compared to the South China Sea.
* Future Projections: Forecasts indicated continued sea level rise, with potential increases of X millimeters per year in the short term and Y millimeters by 2034.
Visualizations:
* Historical Trends: Time series plots for each selected sea.
* Forecast Models: Predictive plots showing future scenarios.
Issues and Resolutions:
* Unresolved Data Anomalies: Some anomalies could not be fully resolved, leading to potential minor inaccuracies in trend analysis. We documented these issues and noted their potential impact on the results.
Next Steps
Potential Next Steps:
1. Extended Research: Incorporate recent data and additional climate variables to refine forecasts and extend the analysis.
2. Advanced Modeling: Develop and test more sophisticated models, including machine learning approaches, to improve prediction accuracy and account for complex interactions in the data.
3. Regional Focus: Conduct in-depth studies of specific coastal areas to provide targeted recommendations for adaptation and policy.
Other Sources:
Pacific Ocean:
- https://www.soest.hawaii.edu/soestwp/announce/news/study-reveals-how-volcanic-eruptions-affect-el-nino/
- https://www.climate.gov/news-features/blogs/enso/has-climate-change-already-affected-enso#:~:text=The%20warmer%20surface%20layer%20enhances,and%20La%20Ni%C3%B1a%20more%20extreme.
- https://sealevel.nasa.gov/faq/10/how-does-el-nino-fit-into-the-sea-level-rise-picture/
- (Mahapatra, S., & Mishra, S. (2023). The Indian Ocean's warming and its impact on regional sea level rise. Global and Planetary Change. https://doi.org/10.1016/j.gloplacha.2023.104239)
- Harman, C. (2023). An analysis of sea level rise patterns and contributing factors. Scientific Reports, 13, Article 48136. https://doi.org/10.1038/s41598-023-48136-y
- “2022 Sea Level Rise Technical Report.” NOAA’s National Ocean Service, 15 Feb. 2022, oceanservice.noaa.gov/hazards/sealevelrise/sealevelrise-tech-report.html#:~:text=About%202%20feet%20(0.6%20meters,the%20end%20of%20this%20century.
- Lindsey, Rebecca. “Climate Change: Global Sea Level.” NOAA Climate.Gov, 19 Apr. 2022, www.climate.gov/news-features/understanding-climate/climate-change-global-sea-level#:~:text=The%20rising%20water%20level%20is,record%20(1993%2Dpresent). 
