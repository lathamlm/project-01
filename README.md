# project-01
## Project 1

________________________________________________________________________

### PROJECT TITLE : 

"Data Science Salaries - Managing Expectations"

________________________________________________________________________
   
### TEAM MEMBERS:

* Leah Latham
* Jonah Foeday
* Manroop Gill
* Murtatha Alwan

________________________________________________________________________

### PROJECT DESCRIPTION/OUTLINE:  

* Jupyter Notebook
1. Import, read, and display CSV file
2. Identify top-5 countries by volume and calculate average salary for each country by year
3. Identify company sizes and calculate average salary for each size by year
4. Create line graphs for task #2 and #3
5. Create summary statistics for job title and experience level
6. Create boxplots for job title and experience level
7. Create pie chart by job title and experience level
8. Identify latitude and longitude using geoapify API for country lists
9. Create geomaps for US companies and US residents
10. Save images to file

* Presentation
1. Assemble graphs/maps from ipynb file
2. Summarize findings

________________________________________________________________________

### RESEARCH QUESTIONS TO ANSWER:

1. How have data science salaries changed over time?  (by country and company size)
2. What is the breakdown of experience level required for data science jobs, and how do they vary?
3. What is the breakdown of job titles for data science jobs, and how do they vary?
4. Do US companies hire US residents, and do US residents work for US companies?

________________________________________________________________________

### DATASET(s)/API(s) TO BE USED:

Data Science Salaries: 2020-2023 https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023

Geocoder API: (https://apidocs.geoapify.com/docs/geocoding/forward-geocoding/#api)

________________________________________________________________________

### ROUGH BREAKDOWN OF TASKS:

* Leah Latham - geomaps and summary
* Jonah Foeday - pie graph, boxplot, and summary statistics
* Manroop Gill - pie graph, boxplot, and summary statistics
* Murtatha Alwan - Intro and line graphs
* Combined - Write-up and PPT

_________________________________________________________________________

## REFERENCES / RESOURCES

* hvPlot customization : https://hvplot.holoviz.org/user_guide/Customization.html
* class activities / slides

_________________________________________________________________________

## ANALYSIS AND CONCLUSION

1. How have data science salaries changed over time?  (by country and company size)
- Data science salaries have increased over time with medium size companies showing the highest growth and US companies consistently offering the highest average salary
- 89.8% of the company locations in the dataset were the top 5 countries (US, UK, Canada, Germany, and Spain), with 75.6% of overall company locations housed in the US
- In addition to showing the most growth, medium-sized companies were also the most common with 2707 out of 3300 jobs

2. What is the breakdown of experience level required for data science jobs, and how do they vary?
- The experience level breakdown is as follows: Entry level (8.8%), Mid level (24.2%), Senior level (62.6%), and Executive level (4.4%)
- Jobs requiring Entry-level experience had a mean salary of $ 80,000 USD and a median salary of $ 70,000 USD
- Jobs requiring Executive-level experience had a mean salary of $ 191,500 USD and a median salary of $ 192,000 USD
- As expected, an ANOVA test showed a stastically significant difference in salary with a p-value of 3.974 e-116

3. What is the breakdown of job titles for data science jobs, and how do they vary?
- The job title breakdown is as follows: Data Engineer (31.5%), Data Scientist (28.5%), Data Analyst (20.6%), Machine Learning Engineer (13.5%), Analytics Engineer (5.9%)
- Data Analyst positions made up 20.6% of the 5 most common jobs, with the lowest mean salary among that group ( $ 110,000 USD)
- Machine Learning Engineer positions made up 13.5% of the 5 most common jobs, with the highest mean salary among that group ($ 167,000 USD)
- An ANOVA test showed a stastically significant difference in salary with a p-value of 9.11 e-35

4. Do US companies hire US residents, and do US residents work for US companies?
- US companies hired employees from 30 different countries, and 98.1% of the employees hired were also US residents
- US residents worked for companies in 6 different countries, and 99.8% of the companies were also located in the US
- Though the UK had the overall second highest job volume, no UK companies hired US residents, and no US residents worked for UK companies