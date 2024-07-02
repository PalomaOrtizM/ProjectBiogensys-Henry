## Strategic Expansion of Laboratories for COVID-19 Research and Vaccination

### Project
The purpose of the BIOGENESYS project was to identify the optimal location for expanding its pharmaceutical laboratories, aiming to enhance response capabilities to the challenges posed by the COVID-19 pandemic and improve vaccine accessibility. The analysis was based on several key criteria: population density, healthcare infrastructure, effectiveness of vaccination campaigns, economic conditions, and climate suitability.

### Tools 
- **Python**
  - Librarys: Pandas, Numpy, Matplotlib, Seaborn
- **Jupyter Notebooks**
- **PowerBi**
- **Visual Studio Code**
  
### Project Development
I started the initial progress by familiarizing myself with the data, examining the columns and how the records in the columns were represented. Then I continued loading the dataset with the cleaning performed by the data scientists. There were missing values in several columns, and I proceeded to fill in the nulls, using the average for some columns and simply using 0 for others, considering whether it would significantly bias the information or not.
The dataset contained around 22 million records and 707 columns.I would have liked to improve the data, but due to time constraints, I couldn't. Ideas came to me when I reached Power BI. However, I decided to work with the data I already had.
I created each graph with the help of the lectures, the professor, and artificial intelligence. Since I don't have much knowledge about the pharmaceutical industry, I did a lot of online research to obtain useful graphs and metrics.

[EDA](https://github.com/PalomaOrtizM/ProjectBiogensys-Henry/blob/main/EDA_PIDA.ipynb) (Exploratory Data Analysis )
 - Correlation Charts: Identification of relationships between variables.
 - Bar Charts and Histograms: Comparison of categorical data and data distribution.
 - Scatter Plots: Analysis of variables such as new confirmed cases and temperature.
 - Line Charts: Temporal evolution of vaccine dose administration and COVID-19 cases.

### Dashboard 
I used a script to connect the cleaned database to Power BI and started creating visualizations.In Power BI, I added columns to facilitate the calculation of metrics and normalized some data to avoid incorrect numbers.
 - Home Page:Upon opening the dashboard, an overview is presented, including key metrics such as total population, new confirmed cases, deaths, and administered vaccines. Interactive widgets allow users to quickly select any country of interest and view related specific data.
 - Demographic Factors:This section features charts showing the age distribution of the population and population density by country. Using filters, users can explore different countries to identify those with a high proportion of at-risk population due to age.
 - Economic Factors:Here, visualizations of GDP per capita and the monthly variation of confirmed cases and deaths are found. A line chart shows the trends of these indicators over time, providing insights into how economic conditions may influence public health. This tab contains detailed charts on the doses of vaccines administered over time in different countries, along with comparative vaccination coverage. This is crucial for evaluating the effectiveness of vaccination campaigns and planning future distributions.


### Conclusions and Recommendations

#### Conclusions:
- Population Density and Demographics: Analyzed age distribution and population density in various Latin American countries. Chile and Argentina showed high urban population densities and significant elderly populations, highlighting ongoing demand for healthcare services.
- Healthcare Infrastructure: Chile demonstrated a robust healthcare infrastructure with a sufficient number of doctors per capita, supporting extensive healthcare activities including clinical trials and laboratory services.
- Vaccination Effectiveness: Chile and Argentina exhibited higher vaccination coverage rates compared to peers, indicating effective public healthcare systems and strong public acceptance of medical interventions.
- Economic Stability: Chile's higher GDP per capita suggests greater access to advanced medical treatments, bolstering its attractiveness as a healthcare destination.
- Climate Conditions: Chile's favorable climate offers optimal conditions for pharmaceutical product storage and logistics, enhancing operational efficiency.
#### Recommendations:
Based on the analysis, Chile is recommended as the preferred location for establishing the new BIOGENESYS laboratory. Its combination of robust healthcare infrastructure, effective vaccination programs, economic stability, and favorable climate provides a conducive environment for pharmaceutical operations.

### Next Steps
- Implementation Planning.
- Continued Analysis.
  
### Personal Reflection:
This project has enabled me to apply my data analysis skills to make informed decisions based on multiple variables, which is an essential skill for any data analyst in the healthcare sector. I would have liked to study more about the pharmaceutical industry. As an analyst, I understand the importance of being prepared to handle various scenarios, and I believe that my background has greatly assisted me in making better decisions in this project and will continue to benefit me in the future.


**If you've read this far, *THANK YOU!* I will continue improving this project and many more are about to come.**
