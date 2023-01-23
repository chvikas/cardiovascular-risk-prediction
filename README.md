<h1 align="center"> Cardiovascular Risk Prediction </h1>

<p align="center" width="100%">
    <img width="60%" src="https://img.freepik.com/free-vector/human-internal-organ-with-heart_1308-108889.jpg?w=740&t=st=1674130094~exp=1674130694~hmac=99baf9a75b8b3c84562894523dfaa805e5dd98fafe43966c5dbcdc82d90c7e6e">
</p>

<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>The project categorized the patients based on a 10-year risk of future coronary heart disease (CHD).</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Table of Content</h2>

  * Overview
  * Dataset Information
  * EDA and Feature Engineering
  * Model
  * Result

This project is aimed at categorizing a patient based on the medical history if the patient has any risk of having a cardiovascular disease in the next 10 years.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Overview</h2>

With the help of existing health data this project build a classification Machine Learning (ML) algorithm, it classifies the patients based on the possibility of encountering the cardiovascular risk in the next 10 years. 


<h3> Tools Used: <h3>

1. Python

2. Numpy and Pandas for data cleaning

3. Data visualization

4. Sklearn for model building

5. Jupiter Notebook


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> Dataset information</h2>

Raw Dataset:
<p align="left" width="100%">
    <img width="80%" src="https://user-images.githubusercontent.com/90998859/214115913-fc8cc895-a30e-42b5-8655-ca2fb42aea3b.png">
</p>


The final dataset has the following 16 features (1 dependent + 15 independent):
<p align="left" width="100%">
    <img width="80%" src="https://user-images.githubusercontent.com/90998859/214116796-bc0c6a76-df1b-4ba6-b237-24e30b40791a.png">
</p>

* age

* education

* sex

* cigsPerDay (number of cigarettes smoked per day)

* BPMeds (if the patient is taking BP Medicines)

* prevalentStroke (Prevalent Heart Attack Risk)

* prevalentHyp (Prevalent Hypertension)

* diabetes

* totChol (Total Blood Cholesterol)

* sysBP (Systolic Blood Pressure)

* diaBP (Diastolic Blood Pressure)

* BMI (Body Mass Index)

* heartRate

* glucose

* TenYearCHD (Ten Years Cardiovascular Risk) - Dependent Feature (0 - no risk, 1 - have risk)

* pulse_pressure (difference between Systolic BP and Diastolic BP)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> EDA and Feature Engineering</h2>

The following steps were followed for EDA and Feature Engineering

* Missing Value Treatment (multiple approach)

* Univariate Analysis on numerical features (along with Central Tendency)

* Analyzed datast using graphical and non-graphical methods - (graphical method includes scatter plot, line chart, bar graph, etc)

* Feature Selection

* Some Features like 'is_smoking' were dropped

* New Feature created (pulse_rate)

* Heat map was used to know the correlation among features, and those with higher correlation were dropped.

<p align="left" width="100%">
   <img width="45%" src="https://user-images.githubusercontent.com/90998859/214129170-4993ec3e-da02-462a-b5c3-4810bdbd3a13.png">
 </p>


* Employed 'label encoding' and 'One-hot encoding' to get numerical features from label and categorical features.

* Employed SMOTE (Synthetic Minority Oversampling Technique) to oversample the classes

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Model </h2>

* The dataset was trained on 6 algorithm with k-nn with hyper-parameter tuning as the base algorithm. 

* Other algorithm used are: Decision Tree Classifier, Logistic Regression Classifier, Naive Bayes Classifier, Support Vector Classifier (SVC) and Random Forest

* Employed Hyper-parameter Tuning using GridSearchCV on knn

* Every algorithm was evaluated using Confusion Matrix (both on Train and Test set)
    
<p align="left" width="100%">
   <img width="30%" src="https://user-images.githubusercontent.com/90998859/214125568-be738961-153f-4dff-9cd1-abd0fb41e7b1.png">
</p>

* Classification Report for every algorithm was generated (both on Train and Test set)
    It provides accuracy, precision, and recall for better decision making based on the use case.
<p align="left" width="100%">
    <img width="40%" src="https://user-images.githubusercontent.com/90998859/214124372-b3f23e2f-1a82-40e2-af6b-5d3302a0e0c0.png">
 </p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Result</h2>

<p align="left" width="100%">
    <img width="70%" src="https://user-images.githubusercontent.com/90998859/214122746-a42ae7b3-0fbe-49a3-924b-48b155c9d3f2.png">
 
</p>

knn (k-Nearest Neighbors) with Hyper-parameter Tuning using GridSearchCV has achieved the highest AUCROC Score of nearly 89.3%.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Vikas Chaudhary > | Data Science Enthusiast

<p> <i> Contact me for Data Science Project Collaborations and Research</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/chvikas/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chvikas)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@chvikas)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Technologies Used::</h2>

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://user-images.githubusercontent.com/32620288/139657460-40ef4562-76bd-43f5-bbca-47b6bd29863e.png" width=100>](https://numpy.org)    [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/450px-Pandas_logo.svg.png" width=150>](https://pandas.pydata.org)  [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=150>](https://seaborn.pydata.org) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=170>](https://matplotlib.org)   [<img target="_blank" src="https://user-images.githubusercontent.com/32620288/137518674-f36c5ad3-3d64-4c7a-a07c-53f247750394.png" width=170>](https://colab.research.google.com/)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

