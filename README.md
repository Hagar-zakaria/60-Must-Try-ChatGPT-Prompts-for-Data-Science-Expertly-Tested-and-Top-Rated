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


## 3. Tune Hyperparameter
Prompt: I want you to act as a data scientist and code for me. I have trained a [model name]. Please write the code to tune the hyper parameters.

![image](https://github.com/user-attachments/assets/8b28de02-ac02-40f4-8df6-b111e52f0b57)

![image](https://github.com/user-attachments/assets/4199ec3c-4b3a-438e-acac-eef09b96508d)

For a decision tree classifier, ChatGPT wrote code that:

- performed a grid search
- suggested the best parameters.

Not bad at all, and the code runs! Grid search is the most popular method for hyperparameter tuning, so it’s no surprise that it came up on top.

However, note that grid search goes through the search space exhaustively. The larger the search space, the longer time it will take. An alternative is the randomized search, which implements a randomized search over parameters. Once assigned a budget, randomized search takes the same amount of time regardless of the search space.

## 4. Explore Data
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

##  5. Generate Data

Prompt: I want you to act as a fake data generator. I need a dataset that has x rows and y columns: [insert column names]

![image](https://github.com/user-attachments/assets/b3030930-f8c1-40e9-bbdc-54cfe60302bb)

![image](https://github.com/user-attachments/assets/b204a9b9-9b92-44b4-adc2-2958c8a44d98)


ChatGPT produced code that generated the data as per my requirements completely. It only used the pandas library and the inhouse random library, making it portable. I actually did use the synthetic dataset for other tasks.

## 6. Write Regex

Prompt: I want you to act as a coder. Please write me a regex in Python that [describe regex]

![image](https://github.com/user-attachments/assets/1ae156c0-6d47-4572-bb2c-88f8ce488a38)

![image](https://github.com/user-attachments/assets/beba542c-31db-43ac-85de-2e9982fde829)

This regex uses the following elements:

- ^: This matches the start of the string.
- [a-zA-Z0-9]: This matches any alphanumeric character.
- .*: This matches any number of any characters (except a newline), including none.
- data: This matches the string "data".
- science: This matches the string "science".
- !: This matches the exclamation point.
- $: This matches the end of the string.

Here, ChatGPT provided code that matched a regex as per requirements in Python.

However, note that I have cherrypicked this example. Before this, I had tried asking ChatGPT to create more complex other regex patterns but it failed. It even sounded confident when it explained the regex, but the regex it produced didn’t work.


## 7. Train Time Series 

Prompt: I want you to act as a data scientist and code for me. I have a time series dataset [describe dataset]. Please build a machine learning model that predict [target variable]. Please use [time range] as train and [time range] as validation.

![image](https://github.com/user-attachments/assets/bff9d0b7-ae72-43a1-8c1f-d5da84de597f)

![image](https://github.com/user-attachments/assets/61fc0ef9-6761-4da9-8e44-e155ab2df21b)

![image](https://github.com/user-attachments/assets/fe687970-d98d-4141-b746-dd8602f38f56)

![image](https://github.com/user-attachments/assets/ce495c7c-654a-4c1d-be28-76b030a7b23c)


ChatGPT provided code that:

- preprocessed the data using standard scaling
- Created lag variables
- Trained a RandomForestRegressor for the evaluation
- Used Mean Absolute Error for evaluation

Alright, here’s a controversial one. ChatGPT is not able to properly write code for time series validation.

Here’s why: Without the prompt “please use data from A to B as training. Please use data from Y to Z as validation”, ChatGPT uses sklearn’s train_test_split to randomly splits the data points into train and validation. This is a huge no-no because the train_test_split function randomly splits the data with no regard for the temporal relationship between the datasets. Instead, it should have used all data points from an earlier timeframe as train and later timeframe as test.


## 8. Address Imbalance Data

Prompt: I want you to act as a coder. I have trained a machine learning model on an imbalanced dataset. The predictor variable is the column [Insert column name]. In python, how do I oversample and/or undersample my data?

![image](https://github.com/user-attachments/assets/e2748f38-130d-4355-b592-5b67f629a4e9)

![image](https://github.com/user-attachments/assets/029cc0a2-1dda-4cdd-970e-3dcd89fb6ca4)

To undersample the majority class, you can use the RandomUnderSampler method from the imblearn library. Here is an example of how to use it:

![image](https://github.com/user-attachments/assets/d85b5d28-7b4d-49ef-bb47-0be593844c1c)

ChatGPT used the imblearn library to write boilerplate code that randomly under and oversamples the dataset.

The code is sound, but I would nitpick on its understanding of over and undersampling.

Undersampling and oversampling should only be done on the train dataset. It should not be done on the entire dataset, which includes the test dataset. Otherwise, the evaluation will be done on a resampled test set that no longer reflects the actual distribution of the real dataset.

Thus, it should have attempted to split the dataset into train and test sets first, before performing the under and oversampling.

## 9. Get Feature Importance

Prompt: I want you to act as a data scientist and explain the model’s results. I have trained a decision tree model and I would like to find the most important features. Please write the code.

![image](https://github.com/user-attachments/assets/b200edd4-7724-4919-b4f2-2db136d1519f)


ChatGPT correctly provided the code for plotting the feature importance of a decision tree. It even ranked the feature importances from the most important to the least important. 

## 10. Visualize Data with Matplotlib

Prompt: I want you to act as a coder in python. I have a dataset [name] with columns [name]. [Describe graph requirements]


![image](https://github.com/user-attachments/assets/50246028-289f-4935-bde1-52b277cf5e7b)

![image](https://github.com/user-attachments/assets/16c9c541-0fb8-4407-a19d-bb9f6fd7ee8c)

![image](https://github.com/user-attachments/assets/c7cd51d1-1f18-4350-b5c3-2e389edd94ac)



ChatGPT could provide the correct code for plotting visualizations in Matplotlib.

I am particularly impressed because I provided very long and rather convoluted instructions, and ChatGPT followed them to a tee. Here is the output from the code:

![image](https://github.com/user-attachments/assets/7e54e432-1bfa-4204-a3ff-5ab198d7c76c)

## 11. Visualize Image Grid Matplotlib

Prompt: I want you to act as a coder. I have a folder of images. [Describe how files are organised in directory] [Describe how you want images to be printed]

![image](https://github.com/user-attachments/assets/5638edd1-a4cf-4c86-ac75-71a12efba812)

![image](https://github.com/user-attachments/assets/548a5025-a396-4597-9409-20609acc6dbe)

![image](https://github.com/user-attachments/assets/b83e8c5c-66f6-4037-9c27-447d96960c01)

![image](https://github.com/user-attachments/assets/6735df3b-c8e3-4081-a83f-6990e21860e4)


Again, ChatGPT can provide the correct code for plotting grid of images with Matplotlib.

Again, I provided convoluted and long instructions, but ChatGPT could follow them to a tee. (I personally loathe creating charts with Matplotlib. It is extremely flexible but writing code in it is rather painful.)


## 12. Explain Model with Lime

Prompt: I want you to act as a data scientist and explain the model’s results. I have trained a [library name] model and I would like to explain the output using LIME. Please write the code.

![image](https://github.com/user-attachments/assets/e8267dd4-7ee9-4655-96c6-84899d6b28ee)

![image](https://github.com/user-attachments/assets/49d45dfa-4fba-4aa0-abb3-4ee8456ba42d)


ChatGPT provided code for explaining the model with LimeTabularExplainer and explained an instance with the correct commands.

Personally, I find this helpful because I do not need to refer to the documentations for the boilerplate code. Overall, ChatGPT provided accurate code that does not violate any principles.


## 13. Explain Model with Shap
Prompt: I want you to act as a data scientist and explain the model’s results. I have trained a scikit-learn XGBoost model and I would like to explain the output using a series of plots with Shap. Please write the code.

![image](https://github.com/user-attachments/assets/125249e2-ba6f-4697-843a-8ef8208a5dd6)

![image](https://github.com/user-attachments/assets/00c7d90c-2153-4f0e-9c17-6d1add6bf925)

## 14. Write Multithreaded Functions

Prompt: I want you to act as a coder. Can you help me parallelize this code across threads in python?

![image](https://github.com/user-attachments/assets/6758dab9-19fc-4b5e-8c21-adb64f8d87fa)

![image](https://github.com/user-attachments/assets/e3684b0d-8924-41f1-9806-e8e498d3d196)

I’m pleasantly surprised to find that this code actually works without any modifications. I can foresee myself doing this often in the future.


## 15. Compare Function Speed

Prompt: I want you to act as a software developer. I would like to compare the efficiency of two algorithms that performs the same thing in python. Please write code that helps me run an experiment that can be repeated for 5 times. Please output the runtime and other summary statistics of the experiment. [Insert functions]

![image](https://github.com/user-attachments/assets/6ab4bcb0-cd97-4287-bb30-9d2867905b25)

![image](https://github.com/user-attachments/assets/5ece3d80-15fb-4278-84c3-d35ebcd43125)


ChatGPT is able to write code that compares two function speeds with built-in packages.

The code runs and is correct. Though, I would rather ChatGPT use the %%timeit magic in Python instead of writing verbose code.
