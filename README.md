# Hi there, I'm Aiman and this is My Portfolio!

- An introduction of yourself
- Skills like Data Analysis, SQL, Python, Tableau, Web Development, etc
- Fancier things like visitor count, clickable icons, etc (can't help you with this as I've not learn it yet 😅)
- Projects that you're proud of


## Table of Contents
- [Project 1: IBM Data Scientist Capstone Project, Winning Space Race with Data Science](#project-1-ibm-data-scientist-capstone-project-winning-space-race-with-data-science)
- [Project 2: Data Analysis on Google Universal Analytics Demo Data Using Tableau](#project-2-data-analysis-on-google-universal-analytics-demo-data-using-tableau)
- [Project 3: Maven Cycles Reporting using PowerBI](#project-3-maven-cycles-reporting-using-powerbi)
- [Project 4: EDA on NBA Trends Data using Python](#project-4-eda-on-nba-trends-data-using-python)
- [Project 5: A/B Testing on Commerce User Behavior Data using SQL](#project-5-ab-testing-on-commerce-user-behavior-data-using-sql)

# [Project 1: IBM Data Scientist Capstone Project, Winning Space Race with Data Science](https://github.com/aiman-aisa/IBM-Data-Scientist-Applied-Data-Science-Capstone-Project)
Project Objective: SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch by predicting if the Falcon 9 first stage will land successfully based on dataset from SpaceX API and historical launch records from Wikipedia.
- Utilized SQL to do initial EDA on the collected datasets.
- Utilized folium python library to analyzed launch sites locations
- Created a machine learning pipeline to predict if the first stage will land. Model used includes; 
--   1) K-Nearest Neighbouts 
--   2) Decision Tree
--   3) SVM 
--   4) Logistic Regression.

### Launch Success Rate for all Launch sites:
![](images/Launch%20Success%20Rate.png)

### Highest Success Rate Launch site chart:
![](/images/Highest%20Success%20Rate%20Pie%20chart.png)


### Payload vs Launch Outcome:
![](/images/Payload%20vs%20Launch%20Outcome.png)


### Accuracy of each Machine Learning Prediction Model:
![](/images/ML%20Accuracy.png)


### Confusion Matrix of the Best Classification model:
![](/images/Confusion%20Matrix%20of%20the%20best%20Classifier.png)


# [Project 2: Data Analysis on Google Universal Analytics Demo Data Using Tableau](https://github.com/aiman-aisa/TalentLabs-Foundation-Certificate-in-Data-Analytics/tree/main/3.%20Capstone%20Project)
Project Objective: To analyse the location report data for the United States from the Google Universal Analytics Demo Account for the whole 2021. 
-  Prepared the file from Google Universal Analytics Demo Account for data wrangling.
-  Cleaned the data by checking the formats, removing duplicates, erros, null values and unnecessary elements in the data.
-  Built a dashboard using Tableau to visualize the analyzed data into four different charts.

![](/images/Dashboard%201.png)

# [Project 3: Maven Cycles Reporting using PowerBI](https://github.com/aiman-aisa/Maven-Cycles-Reporting)
Project objective: To built and end-to-end business intelligence solution for Maven Cycles, a boutique bicycle equipment shop, using raw data containing information about sales, products, customers, and store locations.
- Utilized Microsoft Power BI to design, build and deploy reports and dashboards to share accross organization
- Found out that the product which has highest quantity sold is in the accessories category using the key influencers.
- Built the decomposition tree from country, product category to age group to understand the distribution of the customers in contributing to the total revenue of the business.   

### Dashboard
![](/images/Executive%20View.png)
### Key Influencer
![](/images/Key%20Influencers.png)
### Decomposition Trees
![](/images/Decomposition%20Trees.png)
### Clustering & Grouping
![](/images/Clustering%20%26%20Grouping.png)

# [Project 4: EDA on NBA Trends Data using Python](https://github.com/aiman-aisa/CodeCademy_DataScientist_MLSpecialist/tree/main/Module%208:%20EDA%20in%20Python)

![]()

# [Project 5: A/B Testing on Commerce User Behavior Data using SQL](https://github.com/aiman-aisa/Data-Wrangling-Analysis-and-AB-Testing-with-SQL/tree/main/Final%20Project)

## Lift and P-values
- Control success rate: 82%
- Treatment success rate: 84%
- Lift of 2.6%
- p-value of 0.20
- The test group 1 had 2.5% more viewed items compared to test group 0, the p-value for this lift was 0.2 which  does not meet our threshold for signiȜicance. There is no statistically signiȜicant change to the metrics viewed percent as a result of the treatment.

![](/images/Percent%20of%20Items%20Viewed%20by%20Test%20Group.png)
![](/images/Average%20Views%20per%20item%20by%20Test%20Group.png)
