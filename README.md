# [Project 1: Web Scraping and Data Analysis](https://github.com/dabykov/Projects/tree/main/project-1)
The goal of this project was to build a dataset that contains general information about major old Hollywood figures. In order to do it, I implemented several steps:
<ul>
<li> Scraped Wikipedia webpages of 196 figures using BeautifulSoup library. </li>
<li> Transformed and cleaned the data for it to be usable for exploratory analysis using such libraries as Pandas, Numpy, and Regex. </li>
<li> Engineered features and augmented data.</li>
<li> Performed exploratory data analysis and visualized the results in order to gain interesting insights using Matplotlib library.</li> </ul>

![](https://github.com/dabykov/Data-Science-Portfolio/blob/main/docs/assets/dashboard%201_1.png?raw=true)

# [Project 2: New York Airbnb Price Prediction Model](https://github.com/dabykov/Projects/tree/main/project-2)
 The goal of this project was to build a predictive regression model that estimates Airbnb prices in New York City. In order to do it, I implemented several steps:
 <ul>
    <li> Cleaned the data for it to be usable for exploratory analysis using such libraries as Pandas and Numpy</li>
    <li> Performed exploratory data analysis for 12 variables, which included calculating key statistical metrics, examining correlation between numerical variables, performing analysis of variance.</li>
    <li> Visualized variables in order to gain insights into data distribution, proportions, and values counts, using Matplotlib and Seaborn libraries.</li>
    <li> Engineered features, which included feature scaling, one-hot encoding, and deimensionality reduction.</li>
    <li> Trained and tested three different regression models: </li></ul>
    
        	Random Forest regression (R-squared: 99.9%)
        	Gradient Boosting Regression (R-squared: 99.9%)
        	KNN Regression (R-squared: 94.3%).

![](https://github.com/dabykov/Data-Science-Portfolio/blob/main/docs/assets/Dashboard%202.png?raw=true)


# [Project 3: Bank Customer Churn Prediction Model](https://github.com/dabykov/Projects/tree/main/project-3)
The goal of this project was to build a predictive classification model that estimates whether a certain bank customer is likely to leave. In order to do it, I implemented several steps:
 <ul>
    <li> Cleaned the data so it would be usable for exploratory analysis using such libraries as Pandas and Numpy</li>
    <li> Performed exploratory data analysis for 14 variables, which included calculating key statistical metrics, examining correlation between numerical variables, and performing analysis of variance.</li>
    <li> Visualized features in order to gain insights into data distribution, proportions, and values counts, using Matplotlib and Seaborn libraries.</li>
    <li> Engineered features, which included feature scaling, one-hot encoding, and target imbalance handling</li>
    <li> Trained and tested seven different classification models: </li>
    
|  | Model	| Training Accuracy	| Test Accuracy|
|--|-------|-----------------|--------|
|1	| LogisticRegression	| 0.704252	| 0.710548|
|2	| RandomForestClassifier	| 0.855759	| 0.825241|
|3	| KNeighborsClassifier	| 0.835307	| 0.811009|
|4	| GaussianNB	| 0.709903	| 0.722687|
|5	| SVC	| 0.797094	| 0.795521|
|6 |	AdaBoostClassifier	| 0.783459	| 0.789870|
|7	| GradientBoostingClassifier	| 0.828938	| 0.824404|

  <li> Built an ensemble model from three best-performing models with accuracy value at 82.7% </li>
</ul>

![](https://github.com/dabykov/Data-Science-Portfolio/blob/main/docs/assets/Dashboard%203.png?raw=true)


# [Project 4: UFC Fighters Segmentation using K-means](https://github.com/dabykov/Projects/tree/main/project-4)
The goal of this project is to perform a clustering analysis that would segment UFC fighters into different groups based on their characteristics available. In order to do it, I implemented several steps:
 <ul>
    <li> Cleaned up the data for it to be suitable for exploratory analysis using such libraries as Pandas and Numpy.</li>
    <li> Performed exploratory data analysis for 6 variables, which included calculating key descriptive statistics, examining the correlation between numerical variables, and assessing the frequency distribution of each using Matplotlib and Seaborn libraries.</li>
    <li> Performed data preprocessing, which included feature scaling, dimensionality reduction, and defining the optimal number of clusters using the Elbow method.</li>
    <li> Applied K-means clustering algorithm and visualized the results. </li>
    <li> Evaluated the results and profiled each cluster in the following way: </li>


| Cluster 1 | Cluster 2	| Cluster 3	| Cluster 4 |
|--|-------|-----------------|--------|
| Young fighters	| Highly experienced both in UFC and MMA	| Young fighters	| Very experienced in MMA, decent experience in UFC |
| UFC newcomers	| Mostly fighters of mature age	| UFC newcomers	| Mostly mature fighters |
| Mostly middle-weight, heavy-weight categories | Weight categories vary significantly	| Mostly light-weight, middle-weight categories| Weight categories vary significantly |
| Tall fighters	| Mostly tall fighters	| Fighters of smaller height	| Middle-height fighters |

![](https://github.com/dabykov/DANIIL_BYKOV/blob/main/docs/assets/Dashboard%204.png?raw=true)
