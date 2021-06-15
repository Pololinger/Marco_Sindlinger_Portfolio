

### 1) [www.CoronaKarte.info](www.CoronaKarte.info)
A website keeping track of the spread of COVID-19 in Germany. Includes key statistics on cases and on the vaccination progress
* Data pipeline from APIs and web scraping to Azure Cloud
* Data cleaning and transformation with Pandas
* Data visualization with Plotly
* Front-End Development, mobile optimization with Dash /Flask and CSS
* Automation with Azure Resource Manager, Runbooks
* Deployment with Docker
* Animation of the data for social Media, [Link](https://twitter.com/Coronakarte)

![CoronaKarte][1]

Visit [CoronaKarte.info](www.CoronaKarte.info)



### 2) [Geospatial Data Analysis with PySpark & Clustering](https://github.com/Pololinger/USGS-EarthquakeData-in-PySpark)

Clustering Earthquakes based on their location with the challenge of calculating distances on a sphere, instead of Euclidian distance

* USGS earthquake data retrieval via API
* EDA with PySpark, Koalas and Plotly
* K-Means with PySpark's MLlib 
* DBSCAN with sklearn

![DBSCAN][2]

###### Clustering on a sphere with DBSCAN using haversine distance

### [3) Text Review Web Scraper with Selenium](https://github.com/Pololinger/selenium_online_shop_web_scraper) 

* Collects product reviews and details from the JavaScript heavy [dm onlineshop](https://www.dm.de/) with semi-infinite scrolling
* Stores the reviews in handy JSON format for storage in MongoDB 

![dm_image][3]

### [4) Customer Segmentation & Order Forecasting](https://github.com/Pololinger/rfm_score_clustering_and_time_series_forecast)

* Aggregating the Superstore data to obtain recency, frequency and monetary (RFM) score
* Clustering with K-Means
* Time-Series forecast with Facebook's Prophet

![forecast][4]


### [5) Spotify dataset - EDA, binary & multilabel classification with Sklearn](https://github.com/Pololinger/Spotify-Song-DF-Explore-and-Predict)

* EDA with pandas, seaborn, and plotly
* Multilabel classification: Predicting the genre with classifiers such as Random Forest, AdaBoost & Neural Network
* Binary classification: Predict whether a song is 'unpopular' or 'popular' with Logistic Regression, Decision Tree and Random Forest


![Confusion_Matrix][5] 
![Correlation_Matrix][6]


### 6) [Cleaning YouTube Subtitles with RegEx & num2words](https://github.com/Pololinger/subtitle_cleaning_with_num2words)

* Replaces tokens according to a user defined dictionary
* Finds digits that are not part of the timestamp
* Transform those digits with num2words to written numbers in almost any language

![andrew][7]


### 7) [Web Scraping Earthquake Data with Beautiful Soup](https://github.com/Pololinger/TurkeyEarthquakeDataCrawler)

* The BDTIM Bogazici University Earthquake Center publishes always the 500 most recent earthquakes in Turkey on its website
* This scraper collects this data and puts into a .txt
* The .txt is cleaned and a dataframe as .csv is exported


![earthquake][8]


[1]: ./assets/CoronaKarte.PNG
[2]: ./assets/dbscan.png
[3]: ./assets/dm.png
[4]: ./assets/forecast.png
[5]: ./assets/confusion_matrix.png
[6]: ./assets/genres.png
[7]: ./assets/subtitles.png
[8]: ./assets/earthquake.png
