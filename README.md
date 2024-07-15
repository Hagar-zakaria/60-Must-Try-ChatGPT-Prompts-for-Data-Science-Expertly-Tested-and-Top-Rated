# 60-Must-Try-ChatGPT-Prompts-for-Data-Science-Expertly-Tested-and-Top-Rated
Streamline Your Data Science Workflow with ChatGPT Automation

![image](https://github.com/user-attachments/assets/72e3694d-d4ce-4560-a252-2faae1b4ca74)

I Rated 60 ChatGPT Functions for Data Science: Discover These Prompts to Have ChatGPT Write and Explain Code, Optimize Data Science Scripts, Clarify Concepts, Suggest Ideas, and Troubleshoot Issues.

# Table of Contents

### Write Python
- Train Classification Model
- Automatic Machine Learning
- Tune Hyperparameters
- Explore Data
- Generate Data
- Write Regex
- Train Time Series
- Address Imbalanced Data
- Get Feature Importance
- Visualize Data with Matplotlib
- Visualize Image Grid with Matplotlib
- Explain Model with Lime
- Explain Model with Shap
- Write Multithreaded Functions
- Compare Function Speeds
- Create NumPy Array
- Write Unit Test
- Validate Column

### Explain Code
- Explain Python
- Explain SQL
- Explain Google Sheets Formula
  
### Optimize Code
- Improve Code Speed
- Optimize Pandas
- Optimize Pandas Again
- Optimize Python
- Optimize SQL
  
### Format Code
- Simplify Python
- Write Documentation
- Improve Readability
- Format SQL
  
### Translate Code from One Language to Another
- Translate Between DBMS
- Translate Python to R
- Translate R to Python
  
### Explain Concepts
- Explain to Five-Year-Old
- Explain to Undergraduate
- Explain to Professor
- Explain to Business Stakeholder
- Explain Like Stack Overflow
  
### Suggest Ideas
- Suggest Edge Cases
- Suggest Dataset
- Suggest Portfolio Ideas
- Suggest Resources
- Suggest Time Complexity
- Suggest Feature Engineering
- Suggest A/B Testing Steps
- Career Coaching
  
### Troubleshoot Problems
- Correct ChatGPT Code
- Correct Python Code
- Correct SQL Code
- Troubleshoot PowerBI Model
  
### Write SQL
- Create Running Average
- Solve Leetcode Question

### Write Other Code
- Write Google Sheets Formula
- Write R
- Write Shell
- Write VBA
  
### Miscellaneous
  - Format Tables
  - Summarize Book
  - Summarize Paper
  - Provide Emotional Support

# WRITE PYTHON
## 1. Train Classification Model
Prompt: I want you to act as a data scientist and code for me. I have a dataset of [describe dataset]. Please build a machine learning model that predict [target variable].

![image](https://github.com/user-attachments/assets/3c032e58-2062-415a-b7df-6cbb85bab248)

![image](https://github.com/user-attachments/assets/697cced4-39d8-434d-89a3-93b4abba7955)

![image](https://github.com/user-attachments/assets/f59c9afb-aa5e-4473-aa16-6f900c6d3955)

![image](https://github.com/user-attachments/assets/bbd7c341-7aca-48ab-bd23-ad1158b2bbac)


ChatGPT is able to provide satisfactory code that:

- provide the regular preprocessing (scaling the data and encoding categorical variable),
- drop the testing column
- provide the train-test split
- evaluate the model
  
This is good because it provides enough code to start off a model. It is also technically sound and correct. However, it’s lacking because it only uses accuracy for evaluation.

## 2. Automatic Machine Learning
Prompt: I want you to act as an automatic machine learning (AutoML) bot using TPOT for me. I am working on a model that predicts [...]. Please write python code to find the best classification model with the highest AUC score on the test set.

![image](https://github.com/user-attachments/assets/73776935-87bc-486a-9a7e-c67f3d85796a)

![image](https://github.com/user-attachments/assets/f7d58423-3fea-4705-8681-8f2d4fc706f7)

This Python code uses the TPOT (Tree-based Pipeline Optimization Tool) library to automate the process of finding the best machine learning model for predicting whether a person will default on a credit card loan. 


ChatGPT provided good code (it runs!) that:

- provide the train-test split
- instantiated the AutoML classifier
- fit it to the AutoML classifier
- export the classifier
  
I’m not at all surprised that ChatGPT excels here since the code is pretty much only boilerplate code. This can be copied and pasted from the documentation as is.


3. Tune Hyperparameter
Prompt: I want you to act as a data scientist and code for me. I have trained a [model name]. Please write the code to tune the hyper parameters.

![image](https://github.com/user-attachments/assets/8b28de02-ac02-40f4-8df6-b111e52f0b57)

![image](https://github.com/user-attachments/assets/4199ec3c-4b3a-438e-acac-eef09b96508d)

For a decision tree classifier, ChatGPT wrote code that:

- performed a grid search
- suggested the best parameters.

Not bad at all, and the code runs! Grid search is the most popular method for hyperparameter tuning, so it’s no surprise that it came up on top.

However, note that grid search goes through the search space exhaustively. The larger the search space, the longer time it will take. An alternative is the randomized search, which implements a randomized search over parameters. Once assigned a budget, randomized search takes the same amount of time regardless of the search space.

4. Explore Data
Prompt: I want you to act as a data scientist and code for me. I have a dataset of [describe dataset]. Please write code for data visualisation and exploration.

![image](https://github.com/user-attachments/assets/4489fda7-c21a-4c84-9e5b-6f040fd22d8c)

![image](https://github.com/user-attachments/assets/ebfab583-26e7-4316-bf5c-02e5a254f4ed)

For an exploration, ChatGPT wrote code that:

- used df.describe() to provide descriptive statistics
- created count plots for visualizing the distribution of categorical variable
- created a heatmap to determine the between numerical variables
- determined the relationship of numerical variables and the target variable with box plots of numerical columns
- determined the relationship of categorical variables and the target variable with barplot.
- The above choices of charts are indeed correct.
