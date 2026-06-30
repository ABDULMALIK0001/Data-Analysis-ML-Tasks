# Report Of Project Data Analysis 2

## Inroduction and ObJectives : 

In this project, we worked on three main tasks, and each task is characterized by its own methodology and different from the other, through which we learned many skills and gained more knowledge in data analysis, and we also learned about a new field in the world of data analysis, which is text analysis by analyzing sentiment, and it was useful to apply and learn it during this chapter,  In addition to learning another approach, which is market basket analysis, which was one of the interesting and wonderful topics as well, our goal is to provide work according to the organization and clear steps and its concept to obtain the best possible results and avoid any obstacle that would constitute damage to the results of the analysis, during this simplified report we will present our work and what we have accomplished during the three tasks . 

## About Tasks : 
The details of the tasks will be as follows : 

## The First Task : Naive Bayes Model 
In this task, we implemented the Naive Bayes algorithm using the Titanic dataset.  Preload and manipulate data, followed by the implementation of two types of Model ,  Gaussian Naive Bayes and Bernoulli Naive Bayes , adjust hyperparameters using GridSearch, and visualize the results. The purpose of this task is to build a model that can predict values based on a probability classification . <br>
link dataset:[https://www.kaggle.com/c/titanic/data]


What was accomplished and worked on was as follows : 

### The first Step 1 : Exploratory Data Analysis
Where important information was presented that helped us understand the data more, we used the visualization of the data of the type Scatter Plot, to identify problems and check for outliers. 

### The Second Step 2 : Data Cleaning
Our dataset, it contained missing data in some columns, so it was handled and cleaned, using methods like fillna(), dropna(), also the categorical data was converted into digital data during this stage, so that the model understands it and does the classification process correctly. 

### The third step 3:  Build The Model
At this point, we used two different types of Naive Bayes, namely Gaussian and Bernoulli algorithms, in fact there was not much difference in the results of the two types, but both of them were able to get good results. 

### The Fourth step 4 : Evaluation The Model
Here the classification results were calculated, such as accuracy and Recall, F score, persicion , also creating the confusion matrix .

### The fifth step  5 : Using  optimized methods, such as GridSearchCV and Random Forest Algorithm
GridSearchCV combined with the Random Forest algorithm is used to optimize model performance by systematically searching for the best hyperparameters through cross-validation. Random Forest, an ensemble learning method, builds multiple decision trees and reduces overfitting, while GridSearchCV evaluates different hyperparameter combinations (e.g., number of trees, depth) to identify the best configuration. This approach improves model accuracy, generalization, and efficiency by automating the tuning process, resulting in better predictions for Classification

That was all about our work on the first Task....
 ***

## The Second Task : Market Basket Analysis
In this task, we focused on analyzing the purchasing patterns within a dataset using Market Basket Analysis (MBA). The goal was to uncover relationships between products, identify frequently bought together items, and derive actionable insights that could assist in decision-making processes, such as marketing strategies and product recommendations. By transforming unstructured transactional data into a structured format, we were able to apply MBA techniques, leading to a better understanding of customer behavior.<br>
link dataset:[https://archive.ics.uci.edu/ml/datasets/online+retail]

### The first Step 1 : Understanding the Dataset and Exploratory Data Analysis
In this step, we reviewed the dataset to understand its structure and content. We explored basic statistics and visualized data patterns to gain insights into the purchasing behavior

### Step 2: Preprocessing and Data Transformation
In this step, we prepared the data by handling missing values, standardizing text, and removing duplicates and negative numbers. First, we dropped rows with missing descriptions, made product names lowercase, and removed extra spaces. We also removed rows with negative quantities to keep the data accurate and checked for any duplicates. Finally, we created a word cloud of product descriptions to show the most common items, giving a quick view of popular products in the data

### Step 3: Applying Market Basket Analysis (MBA)
In this final step, we used Market Basket Analysis to find product combinations frequently bought together. First, we created a pivot table where each row represented an invoice, and each column represented a product, with quantities transformed into binary values (1 if bought, 0 if not). We then applied the apriori algorithm to find frequent itemsets with at least 3% support, helping us spot popular product combinations. Lastly, we generated association rules to identify strong relationships between items, offering insights that could be useful for targeted promotions or product placement.
***
## The Third Task : Text Analysis 
In this part of the project, we worked on the task of analyzing the text and the content of our dataset related to the sentiment analysis of Twitter tweets, using the most important methods that helped us understand the data that seems to be unclear, into data that we are able to assimilate and understand and extract patterns and relationships from it, then two models of machine learning were built, namely Naive Bayes, Logistic Regression, These two models helped us analyze emotions, and then we evaluated the models and extracted the results. 

Our plan and methodology in working on this task was as follows : 

### The First Step :  Understanding the data 
At this stage, we have installed and imported several libraries related to text analysis, including: NLTK and WordCloud.


### The Second Step : Exploratory Data Analysis (EDA)
The purpose of this stage is to know the details contained in the dataset, extract useful information from the text, and ensure its cleanliness and safety from any missing or annoying values. 


### The Third Step : Text Preprocessing 
This process is very useful, because through it we will classify and represent the words correctly, especially in the stage of building the two machine learning models. 

The treatments we did included the following : 

#### Lowercasing Method  : The goal of this method is to convert words that contain uppercase letters to lowercase letters. 

#### Tokenization method  : They were used, to Split sentences or phrases into Individual words  

#### Stopword Removal method  :  We used it to delete words that are not important or do not affect the analysis because they are not important, such as :  the, in, on, to 

#### Lemmatization & Stemming Methods : These two methods are similar, but Stemming Reducing words to their root forms by stripping suffixes, and Lemmatization it returns valid words.

#### Word Cloud : A word cloud visually represents text data, where word size indicates repetition or significance. Larger words are more common, making them a quick way to identify key topics and terms in text analysis. Our words are categorized into positive and negative . 


### The fourth Step : Feature Extraction and  Build Model Multinomial NB & Logistic Regression 

 we Use The Feature Extraction to convert raw text into numerical data that a machine learning models can understand. We used the technique of TF-IDF . to Weighs words based on their importance in the document and across 
all document . 

After that, we built two machine learning models, Naive Bayes and Logisitic Regression, for the purpose of classification. 

#### Evaluation The Model : 
This stage included the calculation of the accuracy of both sides separately, training and testing, for each of the two models, and then we calculated the average accuracy of each of them, including the results of the Classification Report. We created confusion matrix .


## Conclusion About Our Project :

This project in the data analysis course has been an enriching experience, offering us valuable insights and practical knowledge across various domains of data science. By working on tasks like Naive Bayes classification, Market Basket Analysis, and Sentiment Analysis, we gained hands-on exposure to different methodologies and advanced analytical techniques. Each task provided its own set of challenges, from cleaning and preparing data to building models and extracting actionable insights.

Through this project, we developed key skills such as data preprocessing, feature extraction, and the ability to implement machine learning models. We also explored text analysis, a new and exciting field, allowing us to apply techniques like sentiment analysis and market basket analysis, which deepened our understanding of customer behaviors and relationships within datasets. The experience of evaluating models, optimizing performance, and visualizing data solidified our learning of important concepts like model accuracy, recall, precision, and hyperparameter tuning.

Overall, this project helped us achieve our learning goals, including the ability to analyze and interpret data, build predictive models, and draw meaningful conclusions. The structured approach to each task, combined with the real-world applications, has not only enhanced our technical skills but also cultivated a deeper appreciation for data-driven decision-making.




