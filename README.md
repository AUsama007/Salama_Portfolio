# Salama Portfolio
# [Project 1: Data scientists Salaries](https://github.com/AUsama007/DataScienceSalary) 
 
**Created a tool that estimates data science salaries to help data scientists negotiate their income when they get a job.**

- Scraped over 1000 job descriptions from glassdoor using python and selenium
- Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
- Optimized Linearand Random Forest Regressors using GridsearchCV to reach the best model.

**The Random Forest model far outperformed the other approaches on the test and validation sets.**

Random Forest : MAE = 11.22

Linear Regression: MAE = 18.86
![](https://github.com/AUsama007/DataScienceSalary/blob/main/positions_by_state.png)
# [Project 2: Airbnb predections](https://www.upwork.com/freelancers/~014b7e467604980af7) 
That is my first paid project on UPWORK, those were the points I achieved:

-	Create a price-suggestion model for new Airbnb hosts who might not know the optimal value of their listing.
-	Can we predict the rating of an Airbnb listing?
-	How have Airbnb prices changed over time? What affects the price changes?
-	Can we identify any major driver of visitor’s satisfaction?
-	Which features of an Airbnb listing are important to increase its perceived value?

# [Project 3: Sales Analysis](https://github.com/AUsama007/Data-Science-Sales-Analysis) 

**In this project I have used Python Pandas & Python Matplotlib to analyze and answer BUSINESS QUESTIONS about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.**

We start by cleaning our data. Tasks during this section include:

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

**Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:**

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

# [Project 4: Tinder-Asian](https://github.com/AUsama007/Asian_tinder_Projet)
While using Tinder I faced a problem  with scammers or bots, most of them were using fake asian pictures (unfortunately) as a profile picture. I drevided a model to take a screenshot and do a face classification. If it found that the face is asian it clicks the are of dislike button, press like button otherwise. I used a ready model from a super productive team called mica_race_from_face for race_detection. Used PYAUTOGUI for screen clicking.

# [Project 5: Loan Lending](https://github.com/AUsama007/Loan_Lending_Project)
**For this project I explored publicly available data from LendingClub.com. Lending Club connects borrowers with investors. 
Investors want to invest in people who showed a profile of having a high probability of paying you back. I worked on creating a model that helps in predicting this.
I used lending data from 2007-2010 and tried to classify and predict whether or not the borrower paid back their loan in full.**


# [Project 6: E_Commerce_Predections](https://github.com/AUsama007/E_Commerce_Predections)

**I got some contract work with an Ecommerce company, work with the Ecommerce Customers csv file from the company. It has Customer info, such as Email, Address, and their color Avatar. Based in New York City that sells clothing online but they also have in-store style and clothing advice sessions.
"Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want. The company is trying to decide whether to focus their efforts on their mobile app experience or their website. And That is exactly what the model will be predicting**

# [Project 7:Intrusion Detection System (DKK99 Dataset)](https://github.com/AUsama007/E_Comerce_Predections)

**The study is aiming to build Anomaly based Intrusion Detection System (AIDS) to have a predictive model capable of distinguishing between “bad” connections, called intrusions or attacks, and “good” normal connections using KDD99 Dataset.
KDD99 Dataset contains a wide variety of intrusions simulated in a military network environment. We used Google Colab to utilize the GPU resource in the data** processing and models development 

Before applying any ML algorithm data preprocessing was performed to ensure a well build dataset and accurate results through the below procedures:
- Data Cleaning
- Transformation (encoding)
- Standardization and PCA

Six different models are trained using the 10% of dataset then validated (tested) on the full dataset.
The models are trained to classify multi class of the main connection types (Normal,Dos,R2L,U2R,Probe)
Stratify option is used in the train_test_split method to make a split so that the proportion of values in the sample produced will be the same as the proportion of the attack types in the target variable.

**Result:**
Decision Tree has the lowest processing time in both Training and prediction process.
KNN has the highest prediction time around 82min followed by Random Forest model with around 49 seconds.


# [Project 8: Caviar Sales Data Visualization](https://datastudio.google.com/s/kq4bT7zGrU8)
**A demo project using Google Data Studio**
