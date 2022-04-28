## Hello Folks! Welcome to my data science projects repository!


### About Me

A young and inquisitive electrical engineering graduate who is passionate about artificial intelligence (AI) and machine learning (ML) applications. **Completed Data Science with Python and R course** by 360DigiTMG and Center of Applied Data Science (CADS) **certified Advanced Enterprise Data Analyst Program**. Approximately 1-year of working experience in **program management area** in structured and unstructured data projects. 

Currently, I am focusing on building my data science portfolio through machine learning model development for my data science projects. I am applying exploratory descriptive analysis (EDA) approach for data preparation and supervised and unsupervised algorithms for modelling stage. I will diversify my project's pain points based on my interest and keep on improving my modelling techniques to develop a model with high performance and high accuracy. Feel free to browse through my data science projects and happy to hear your feedback.

*Progress over perfection! Progress can be made, perfection will never arrive*



### Content

- [Project Summary](#Project_Summary)
    * [Project 1: Stock Prices Prediction Model](#Stock-Prices-Prediction-Model)
    * Project 2: *In Progress*
    * Project 3: *Coming Soon*

- [Contact Me](#Contact-Me)



### Project Summary

#### Project 1: 
###### Stock Prices Prediction Model

Develop a supervised machine learning model using Linear Regression (LR) method and Exponential Moving Average (EMA) as a technical                     indicator for stock prices prediction

|Item|Link|
|---|---|
|Data Source (kaggle)|[Blizzard Company Stock Prices Dataset](https://www.kaggle.com/datasets/psycon/game-companies-historical-stock-price-2022-04?select=act_bliz.csv)|
|Python IDE|[JupyterLab](https://jupyter.org/)|
|Source Code|[Stock Prices Prediction LR Model](https://github.com/harishusnan/Project-1-Stock-Price-Prediction/blob/main/Blizzard%20LR%20Model.ipynb)|
|Full Project Details|[Project 1: Stock Prices Prediction Model](https://github.com/harishusnan/Project-1-Stock-Price-Prediction)|


###### Problem Statement

Mr Z is a huge fan of Blizzard company and he has an extra money for an investment. He want to invest in a company with **high reputation** and the **price movement** of its stock prices is **strong uptrend**. It is important for him to analyze the company performance and its stock price pattern before he started to invest his money. Furthermore, identifying the **right time to buy the stock** is his main goal once recognizing the company's stock price pattern.


###### Original Dataset

![Blizzard Dataset](https://github.com/harishusnan/digital-projects/blob/main/images/Dataset.png)


###### Analysis

We checked our dataset if there are outliers exist and we also wanted to see the price movement pattern.

![Boxplot](https://github.com/harishusnan/digital-projects/blob/main/images/Boxplot.png)
![Price_Movement](https://github.com/harishusnan/digital-projects/blob/main/images/Price_Movement.png)

Based on the illustrations above, there are **no outliers exist** in our dataset and the price movement is **strong uptrend**.

Next, we included exponential moving average (EMA) as our technical indicator in developing the prediction model. We decided to calculate the EMA over 10 days period. The output is recorded in the project details (link is provided in the table above). Line chart below shown the comparison between actual price and EMA output after a proper data cleansing.

![Actual vs EMA10 Line Chart](https://github.com/harishusnan/digital-projects/blob/main/images/Actual_vs_EMA10_Linechart.png)


###### Model Development & Evaluation

We split 80% of our data into training dataset and 20% of the remaining data into testing dataset. We trained linear regression model using training dataset and predicted the target values using test dataset. Once we developed the model, we evaluated the model performance through mean absolute error (MAE) and r squared error scores. The error values were shown in the image below.

![Evaluation Metrics](https://github.com/harishusnan/digital-projects/blob/main/images/Evaluation_metrics.png)

Thus, we can conclude that our linear regression model fits our data very well.


##### Application

At this point, we have successfully developed our model and satisfied with the model performance. The next step is to strategise our plan to make a decision whether we should buy/hold/sell the stocks based on the predicted values from our model. So, we created a new column to indicate the call to action (CTA) on each day as shown in the figure below.

![Final Table](https://github.com/harishusnan/digital-projects/blob/main/images/Final_table.png)


I guess that pretty much it! Thank you for your interest and stay tuned for the upcoming projects.


#### Project 2: 
###### *In Progress*



#### Project 3: 
###### *Coming Soon*



### Contact Me

* LinkedIn: https://www.linkedin.com/in/harishusnan/
* Email: mharishusnan@gmail.com

