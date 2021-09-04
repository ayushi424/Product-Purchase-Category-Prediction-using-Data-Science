# Product-Purchase-Category-Prediction-using-Data-Science

### **Introduction**
- This repository contains a project which is Product Purchase Category Prediction using Data Science. 
- It includes prediction of category of product purchased using Machine Learning &amp; Data Science. 

### **Problem Statement** 

For an E-commerce company, based on data from the survey they conducted, perform Data Preprocessing, Feature Selection and Exploratory Data Analytics and then create various Machine Learning Model which will predict the categories on the basis of the various features in the form.
You may use multiple Machine Learning algorithms and compare the performance by error and accuracy check to find which algorithm works best in this case.
Also draw fruitful insights to understand and analyze the data efficiently.


### **Steps followed**

#### Step 1: Data Preprocessing & Exploration. 

- This step includes analysis of data that we will be using in our task.
- This includes perprocessing & exploring the data, to find what different columns it has, shape of the data, datatypes, memory usage, finding null values and treating them accordingly etc.

#### Step 2: Data Visualization.

- This step includes visualization of the data, different columns of data to analyze and understand the relationships between them.
- Most importantly, draw fruitful insights that can be used to modify the existing business plan to enhance both growth & profit. 

#### Step 3: Data Preparation.

- This step includes preparing the available data for data training & model creation.
- Treating categorical columns by converting them into numerical.

#### Step 4: Data Training.

- This step includes spliting the data into traning and tesing data by a specified ratio.
- Training data is the data which is used by the model to train itself.
- Testing data is the data on which the model performs prediction after training itself.

#### Step 5: Model Creation.

- In this we will firstly import the model then initialize it, fit training data into it and then proceed with predictions.
- Here for model creation I have used 4 different models on same training and tesitng data and analyzed their perfromance by accuracy score.

#### Step 6: Performance Analysis.

- In this step, analysed the performance of models used by accuracy check.

### **Libraries used**

- pandas
- matplotlib
- seaborn
- sklearn for importing models and metric

### **Models used**

-  Decision Tree Classifier
-  KNN Classifier
-  Naive Bayes Classfier
-  Random Forest Classifier 

### **Conclusion**

- Model creation is done by using 4 models as Decision Tree Classifier, KNN Classifer, Naive Bayes Classifier and Random Forest Classifier.
- Various features such as age,gender,occupation,city,state,experience rate, product category 1 and product category 2 are included in the training data.
- Target variable is 'Purchase Category' which includes different categories of products as shoes,wallet,watch,perfume,headphones, earphones, books, art & craft supplies, school supplies and office supplies.
- Various models are used on the same training & testing data to find out which model works the best for the data.
- These models based on various features predicts the product category that responder will purchase.
- Decision Tree Classifier & Random Forest Classifier have the same accuracy as 95%
- KNN Classifier have accuracy of 52%
- Naive Bayes classifier have accuracy of 84%

### **Insights drawn**

- The minimum age of responder is 19 years and maximum is 38 years among all the responders.
- Maximum responses (44) are from responders who are of age 33.
- 54.66% of responders are females and 45.34% are males.
- We can say that females are more active to shop from the store then males.
- 51.39% of responders are from Tier 1 city, 40.05% are from Tier 2 city and rest 8.56% are from Tier 3 city.
- We can say that most of the responders who are from Tier 1 city are more active than those of Tier 2 & Tier 3.
- Responders are from 14 different states, where most of them are from Madhya Pradesh.
-  40.55% of the responders are working professionals, 30.73% are students and rest 28.72% are involved in businesses.
- We can say that working professionals are more active on the store as compared ot the students and business people.
- Product category 1 includes 6 different types of products that are: 
1. Earphones,
2. Headphones,
3. Perfume,
4. Shoes,
5. Wallet,
6. Watch.
- Maximum responders chose shoes over other products in Product category 1.
- Product category 2 includes 4 different types of products that are: 
1. Art & Craft Supplies,
2. Books,
3. Office Supplies,
4. School Supplies.
- Maximum responders chose Books over other products in Product category 2.
- 55.16% of the responders visited the store for the first time and rest 44.84% had already visited the store earlier.
- When asked about the experience rate, we got responses for 3,4 & 5.
- Maximum responders were very happy and none of them gave a negative review.

Almost all the columns have positive correlation with other columns which simply means that all columns are corelated to each other.

We can say that important features include:
- Age 
- Experience rate of the responder(1 to 5)
- Gender 
- City
- State
- Occupation
- Product category 1
- Product category 2

However, there was a negative corelation for if the responder is visiting the store first time or already visited before.

### **Author**

[Ayushi Shrivastava](https://github.com/ayushi424)
