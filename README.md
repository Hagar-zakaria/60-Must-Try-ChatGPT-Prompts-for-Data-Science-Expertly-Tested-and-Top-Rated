![image](https://github.com/user-attachments/assets/472254b6-b282-40d5-af8a-e4f35cc5afcc)# 60-Must-Try-ChatGPT-Prompts-for-Data-Science-Expertly-Tested-and-Top-Rated
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

## 16. Create NumPy Array

Prompt: I want you to act as a data scientist. I need to create a numpy array. This numpy array should have the shape of (x,y,z). Please initialize the numpy array with random values.

![image](https://github.com/user-attachments/assets/f9aeb3a5-e706-4b00-87f9-6a93a596a289)


This simple command results in a simple function. Here, ChatGPT demonstrated its ability to translate human language into an appropriate function and parameter.

## 18. Validate Column

Prompt: I want you to act as a data scientist. Please write code to test if that my pandas Dataframe [insert requirements here]

![image](https://github.com/user-attachments/assets/3f9fd972-62f1-4eec-a624-98ba75748289)

![image](https://github.com/user-attachments/assets/3730a1d4-cefc-48fd-9ef2-92f87df50dfe)

![image](https://github.com/user-attachments/assets/cf0994d5-bcf5-4dc1-8c50-482178f4b7c4)

# EXPLAIN CODE

## 19. Explain Python

Prompt: I want you to act as a code explainer. What is this code doing? [Insert code]

![image](https://github.com/user-attachments/assets/746151c3-0720-42fa-8daa-c71cb1fe336c)

I am extremely pleased with ChatGPT’s response with this. Not only is it able to explain concepts for each function. It is also able to guess why the programmer is performing a certain action. For example, it explained the line np.clip(reconstructed, 0, 1) by saying that “this is likely done to ensure that the values are within the valid range for pixel intensity value”, which is absolutely correct.

ChatGPT’s ability to understand code is pretty good and robust, in my opinion. For that, I would strongly suggest any coders who face problems understanding a code use ChatGPT as a complement to the API’s documentation.


## 20. Explain SQL

Prompt: I want you to act as a data science instructor. Can you please explain to me what this SQL code is doing? [Insert SQL code]

![image](https://github.com/user-attachments/assets/fe33aa01-9f90-458f-b5b6-579903cd4ac2)


Again, a correct and an awesome explanation. Much like its explanations for Python, ChatGPT is able to understand and explain SQL code.

I like its explanation of the line SUM(Revenue) OVER (ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW). Note that it’s not only able to provide a high level explanation of what the line is doing, but also provide a breakdown of what the OVER(),UNBOUNDED PRECEDING and CURRENT ROW clauses are doing.

## 21. Explain Google Sheets Formula

Prompt: I want you to act as a Google Sheets formula explainer. Explain the following Google Sheets command. [Insert formula]

![image](https://github.com/user-attachments/assets/5ddfc11f-e881-48cd-ab35-5978d5a784c2)

![image](https://github.com/user-attachments/assets/295f03c1-86b7-412a-87bd-d00059d37632)

ChatGPT is able to explain the FILTER function well. I like that it provided the generalize code snippet like one would see in the documentation, and proceeded to explain the general snippet with the specific arguments provided by the users.

In particular, the line the "Filter" function is being used to filter the range "C2:C12" based on the condition "A2:A12=F2" is an excellent explanation is contextualized to the user’s arguments.


# OPTIMIZE CODE

## 22. Improve Code Speed

Prompt: I want you to act as a software developer. Please help me improve the time complexity of the code below. [Insert code]


![image](https://github.com/user-attachments/assets/32dc0873-f2d7-442a-84f2-9c8e323d8894)


A correct optimization made by ChatGPT from O(n) to O(1). However, note that this is a simple example. You might want to test it on more complex cases to see if this holds up.



## 23. Optimize Pandas

Prompt: I want you to act as a code optimizer. Can you point out what’s wrong with the following Pandas code and optimize it? [Insert code here]

![image](https://github.com/user-attachments/assets/5a7e2d8c-909a-494c-a4da-cef1e24d3e51)

![image](https://github.com/user-attachments/assets/3af3cbbf-16be-4de6-91ff-895a6b8d6605)

I personally think these suggestions are particularly salient. It pointed out that there is nothing wrong with the code (a correct observation) and moved to to suggest good code practices.

## 24. Optimize Pandas Again

Prompt: I want you to act as a code optimizer. Can you point out what’s wrong with the following Pandas code and optimize it? [Insert code here]

![image](https://github.com/user-attachments/assets/bc1115d9-a414-4e24-ab6c-afae0fe3687f)

![image](https://github.com/user-attachments/assets/809c9636-d6f9-4e3f-a9de-52d48729ab98)

Of course ChatGPT is able to catch iterrow as an anti-pattern in Pandas. Love this optimization.

## 25. Optimize Python

Prompt: I want you to act as a code optimizer. The code is poorly written. How do I correct it? [Insert code here]

![image](https://github.com/user-attachments/assets/f8227158-3771-4377-abf9-a5ebe34e38bb)

![image](https://github.com/user-attachments/assets/34573ed8-5b60-4094-a621-b3605b3ebb11)

## 26. Optimize SQL

Prompt: I want you to act as an SQL code optimizer. The following code is slow. Can you help me speed it up? [Insert SQL]

![image](https://github.com/user-attachments/assets/864a1999-bfb7-478b-8921-e6789072d62b)

The first two suggestions here are valid suggestions for optimization. Howeve, the third tip is incorrect. In fact, DATEPART is actually faster than EXTRACT. For that reason, I’ll have to dock stars off for this category.

## 27. Simplify Python

Prompt: I want you to act as a code simplifier. Can you simplify the following code?

![image](https://github.com/user-attachments/assets/dcc2e5ab-23a0-44f1-b8f1-03af1aa534cb)

If you’ve written spaghetti code in Python, ChatGPT might be able to help you simplify it.

# FORMAT CODE

## 28. Write Documentation

Prompt: I want you to act as a software developer. Please provide documentation for func1 below. [Insert function]

![image](https://github.com/user-attachments/assets/8a215cc0-9457-4870-934c-1db5c5e624b1)


ChatGPT could provide a correct, nicely formatted docstring. It also provides a one-liner that captures the essence of the function (“calculates the sum of the integers”). This is neat and I foresee myself doing this a lot.

## 29. Improve Readability

Prompt: I want you to act as a code analyzer. Can you improve the following code for readability and maintainability? [Insert code]

![image](https://github.com/user-attachments/assets/ee7c88cc-242a-488c-97e9-ab6d81c6c875)

I am slightly disappointed here because I had hope ChatGPT would help me remove the redundant variables in the function. That said, its suggestions already did help with readability.

## 30. Format SQL

Prompt: I want you to act as a SQL formatter. Please format the following SQL code. Please convert all reserved keywords to uppercase [Insert requirements]. [Insert Code]

![image](https://github.com/user-attachments/assets/7e95ace4-846e-4b33-8390-87bfe04b8b0f)

The code is formatted nicely and neatly with the correct indentation and casing.

# TRANSLATE CODE

## 31. Translate Between DBMS

Prompt: I want you to act as a coder and write SQL code for MySQL. What is the equivalent of PostgreSQL’s DATE_TRUNC for MySQL?

![image](https://github.com/user-attachments/assets/78392039-fb9b-4031-a620-0e7a4f65a9c9)

While ChatGPT is able to translate the DATE_TRUNC function in this example, it failed on other instances. In particular, it failed to translate the Redshift’s PIVOT into a query that contains a series of CASE WHEN. Thus, this translation might work well only for simple use cases.

## 32. Translate Python to R

Prompt: I want you to act as a code translator. Can you please convert the following code from python to R? [Insert code]

![image](https://github.com/user-attachments/assets/7a6f60f2-2fbf-45b9-ab95-2a2b966d5995)

This is a correct translation! However, note that this is a very straightforward function. ChatGPT might fail on on more complex code blocks.

## 33. Translate R to Python

Prompt: I want you to act as a code translator. Can you please convert the following code from R to python? [Insert code]

![image](https://github.com/user-attachments/assets/3ea49ed8-7eaf-42ff-8b67-5476f411328f)

Again, a correct translation here. However, note that this is a very straightforward function. ChatGPT might fail on on more complex code blocks.

## 34. Explain to Five-Year-Old

Prompt: I want you to act as a data science instructor. Explain [concept] to a five-year-old.

![image](https://github.com/user-attachments/assets/61f8a6ae-f3ed-41e5-be74-3fc5580865d0)

## 35. Explain to Undergraduate

Prompt: I want you to act as a data science instructor. Explain [concept] to an undergraduate.

![image](https://github.com/user-attachments/assets/4b20871c-9c37-487d-86f5-18917044a39b)

## 36. Explain to Professor

Prompt: I want you to act as a data science instructor. Explain [concept] to a professor.

![image](https://github.com/user-attachments/assets/30ce7d06-b923-4ad5-a709-b39336cba0eb)

## 37. Explain to Business Stakeholder

Prompt: I want you to act as a data science instructor. Explain [concept] to a business stakeholder.

![image](https://github.com/user-attachments/assets/77faed77-70e4-4484-975e-0acf1fdcc6b2)

## 38. Explain Like StackOverflow

Prompt: I want you to act as an answerer on StackOverflow. You can provide code snippets, sample tables and outputs to support your answer. [Insert technical question]

![image](https://github.com/user-attachments/assets/03748e7d-7a09-41c5-832d-2b3ba62d997e)

![image](https://github.com/user-attachments/assets/a4b038d7-562a-45bc-aac3-d361c1cc28b2)

## 39. Suggest Edge Cases

Prompt: I want you to act as a software developer. Please help me catch edge cases for this function [insert function]

![image](https://github.com/user-attachments/assets/ef11d27f-fdc1-4dba-9977-6de9019c1eef)

For a relatively simple function, ChatGPT is able to correctly and exhaustively suggests the edge cases. It exhaustively considered all cases without being prompted on what the cases are.

## 40. Suggest Dataset

Prompt: I want you to act as a data science career coach. I want to build a predictive model for [...]. At the same time, I would like to showcase my knowledge in [...]. Can you please suggest the five most relevant datasets for my use case?

![image](https://github.com/user-attachments/assets/a5be07bd-5b4b-4746-88cc-0606680d1160)


I like ChatGPT’s dataset suggestions because they are customized to my use case. I have also tested this prompt for different personas and use cases, and the suggestions it gives are consistently excellent.


## 41. Suggest Portfolio Ideas

Prompt: I want you to act as a data science coach. My background is in [...] and I would like to [career goal]. I need to build a portfolio of data science projects that will help me land a role in [...] as a [...]. 

Can you suggest five specific portfolio projects that will showcase my expertise in [...] and are of relevance to [company]?

![image](https://github.com/user-attachments/assets/d079efdc-a7a8-4e56-8b9b-8226541a3ff3)

This is one of my favourite prompts. Its suggestions are relevant not only to myself, but also to the industry that I am gunning for, and also for my dream company. It does not suggest any generic projects like the Titanic or Iris project. Instead, it makes salient suggestions based on its knowledge of the company (Tesla, in this case), the industry (data science), and my background in engineering.

## 42. Suggest Resources

Prompt: I want you to act as a data science coach. I would like to learn about [topic]. Please suggest 3 best specific resources. You can include [specify resource type]

![image](https://github.com/user-attachments/assets/7df07f0b-91fc-496d-b0e2-2df80f37f78f)

This one is for those looking to learn a new skill. I find that the resources that it has suggested are not only relevant, but also critically acclaimed. It also does not provide an overwhelming list of resources and instead provide only a few. I like this because it certainly provides a good starting point for anyone hunting for new resources.

## 43. Suggest Time Complexity

Prompt: I want you to act as a software developer. Please compare the time complexity of the two algorithms below. [Insert two functions]

![image](https://github.com/user-attachments/assets/1cb17b7a-0b01-41ac-818a-78294366e20b)

## 44. Suggest Feature Engineering

Prompt: I want you to act as a data scientist and perform feature engineering. I am working on a model that predicts [insert feature name]. There are columns: [Describe columns]. Can you suggest features that we can engineer for this machine learning problem?

![image](https://github.com/user-attachments/assets/9663bc6f-db7c-496e-a5e1-38bc19d8dd1d)

I absolutely loved ChatGPT’s reponse here. The features it suggested are sound and actually useful for the use case.

## 45. Suggest A/B Testing Steps

Prompt: I want you to act as a statistician. [Describe context] Please design an A/B test for this purpose. Please include the concrete steps on which statistical test I should run.

![image](https://github.com/user-attachments/assets/d3afed30-34a7-4ab2-abfc-f76201565f65)

![image](https://github.com/user-attachments/assets/af6cbd46-2e0b-4922-8e77-a8b52dbc21b9)

## 46. Career Coaching

Prompt: I want you to act as a career advisor. I am looking for a role as a [role name]. My background is [...]. How do I land the role and with what resources exactly in 6 months?

![image](https://github.com/user-attachments/assets/2ca21f97-33d6-466f-8525-b9e5914f6028)

I have no surprises that ChatGPT did well here. It is able to regurgigate oft-repeated advice for career changers. While this is technically correct, I didn’t find it overwhelming impressive.

# TROUBLESHOOT PROBLEM

## 47. Correct Own ChatGPT Code

Prompt: Your above code is wrong. [Point out what is wrong]. Can you try again?

![image](https://github.com/user-attachments/assets/8a11654e-4e39-42a2-ba8e-8957f4086e8b)

![image](https://github.com/user-attachments/assets/25005f25-6230-4403-b432-634c0ab02e23)

ChatGPT is quick to admit its mistakes and correct its code. In the above example, I asked ChatGPT to create a shell command. I realized that it does not actually run, so I pointed out what was wrong. ChatGPT is able to provide the correct code on the second attempt.

## 48. Correct Python Code

Prompt: I want you to act as a software developer. This code is supposed to [expected function]. Please help me debug this python code that cannot be run. [Insert function]

![image](https://github.com/user-attachments/assets/7ac4f894-2041-416c-9e93-cd2e501a4c0c)

I provided ChatGPT with a simple incorrect function and it is able to tell me why it is wrong correctly.

## 49. Correct SQL Code

Prompt: I want you to act as a SQL code corrector. This code does not run in [your DBMS, e.g. PostgreSQL]. Can you correct it for me? [SQL code here]

![image](https://github.com/user-attachments/assets/239dfa46-2848-414c-8b64-48f98140f3a4)

## 50. Troubleshoot PowerBI Model

Prompt: I want you to act as a PowerBl modeler. Here is the details of my current project. [Insert details]. Do you see any problems with the table?


![image](https://github.com/user-attachments/assets/af46220c-850f-4218-9764-f9e4c6cffafe)

![image](https://github.com/user-attachments/assets/fcf60e7f-30c3-4f1f-967e-e0310fc8a161)


ChatGPT is able to suggest relevant improvements to the PowerBI model. It also admitted its shortcoming (“It’s difficult to determine if there are any problems without more context”)

# WRITE SQL

## 51. Create Running Average

Prompt: I want you to act as a data scientist and write SQL code for me. I have a table with two columns [Insert column names]. I would like to calculate a running average for [which value]. What is the SQL code that works for PostgreSQL 14?

![image](https://github.com/user-attachments/assets/504885d3-9332-49ac-951f-d814a0436733)

![image](https://github.com/user-attachments/assets/81433daf-0cd7-4e2a-80df-f53c49451088)

ChatGPT did provide a good response to the requesst here! It correctly provided the output for creating running averages in SQL. It also provided a correct explanation and breakdown.

## 52. Solve Leetcode Question

Prompt: Assume you are given the tables… with the columns… Output the following…

![image](https://github.com/user-attachments/assets/51dee941-b20f-4321-a697-de32fcf7c615)


# WRITE OTHER CODE

## 53. Write Google Sheets Formula

Prompt: I want you to act as a bot that generates Google Sheets formula. Please generate a formula that [describe requirements]

![image](https://github.com/user-attachments/assets/9d48fee7-d251-4e82-ac52-c44b0010db20)

![image](https://github.com/user-attachments/assets/f925ddd9-a241-4a7e-9b55-363f731e7ac5)

ChatGPT excels at acting as a lookup table for all commands. As you can see, I asked it for a function that pulls one sheet and puts it into another. It faithfully provided the correct importrange.

However, again, I cherrypicked this example. ChatGPT fails when asked to provide more complex formulas. In particular, I asked it to provide a formula that outputs the number of Mondays in 2023. It failed to produce a formula that works. Yet, it still confidently explained it as though it performed splendidly.


## 54. Write R

Prompt: I want you to act as a data scientist using R. Can you write an R script that [Insert requirement here]

![image](https://github.com/user-attachments/assets/8fb789da-db5f-49d6-b20e-38acaa964c11)

ChatGPT sure excelled at this basic R command. This code runs and indeed creates the plot as requested.

However, do note that I did not test ChatGPT on R coding extensively. I can imagine it failing or producing incorrect codes for more complex cases.

## 55. Write Shell

Prompt: I want you to act as a Linux terminal expert. Please write the code to [describe requirements]

![image](https://github.com/user-attachments/assets/753f8a48-ef60-4592-b7fc-d2fcb3825b86)

## 56. Write VBA

Prompt: I want you to act as an Excel VBA developer. Can you write a VBA that [Insert function here]?

![image](https://github.com/user-attachments/assets/4615fdf3-3b02-4ce5-84c5-8850f146c955)

# MISCALLANEOUS

## 57. Format Tables

Prompt: I want you to act as a document formatter. Please format the following into a nice table for me to place in Google Docs? [insert text table here]

![image](https://github.com/user-attachments/assets/aad9c3fa-51ff-4719-85a1-ca63a5b8de66)

## 58. Summarize Book

Prompt: I want you to act as a technical book summarizer. Can you please summarize the book [name] with 5 main points?

![image](https://github.com/user-attachments/assets/c92b4d60-637a-40ae-8f7f-d6232f70a758)

## 59. Summarize Paper

Prompt: I want you to act as an academic. Please summarise the paper [...] in simple terms in one paragraph.

![image](https://github.com/user-attachments/assets/92bb4f76-6d97-4227-8da2-3a579220008b)

60. Provide Emotional Support (My Favourite)
    
Prompt: I want you to provide emotional support to me. [Explain problem here.]

![image](https://github.com/user-attachments/assets/0a9375ea-b3ad-419d-acbb-81304b996b8d)
