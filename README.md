# Data-Analysis-Project----Indian-Start-up-Funding-Analysis
Data analysis of data collected on Indian start-ups funding from 2018 to 2021.

## 1.0 Introduction 
The content article contains an analysis of data collected on Indian start-ups funding from 2018 to 2021.

The rational behind this exploratoration of the data is unearth in details contaited in the different funding opportunies to new businesses and come out with best proposals for young and aspiring enterpreneurs regarding the sectors investors are likely to fund in the Indian start-up ecosystem.

We defined the problem, formulated Hypothesis, asked questions and provided answers to the questions.

### 1.1 Data Handling 
The dataset for each year was loaded from CSV files. New columns were created and column names were changed in the dataset to match that of the other datasets. Irrelevant column was dropped and the four datasets were combined to form a single dataset.

The new column names are:Company/Brand, Founded, HeadQuarter, Sector, What it does,Founders,Investor,Amount($) and Stage

## 2.0 Questioning Stage 
This stage was dedicated to the main analytical work of the project

### 2.1 Hypothses 
Null Hypothesis, H0: There is no relationship between Amount sourced and Industry
Alternative Hypothesis, H1: There is a relationship between Amount sourced and Industry

### 2.2 Questions To Test The Hypotheses 
1. Which Industry received the highest funding?

2. Is there a relationship between the Age of Company and Amount of funding sourced?

3. Which investors give the highest funding?

4. Is location a factor in sourcing funding?

5. Which type of funding is mostly accessed?

6. Which sector attract more investors

## 3.0 Feature Processing 
This stage involves cleaning and processing the features of the dataset

### 3.1 Obtaining Quality Data 
Different libraries including Pandas, Numpy, Seaborn and matplotlib were installed to help us process the data The datasets were loaded, inpected, and called year by year and cleaned. The Indian Rupee was converted to US dollars. Elements that were wrongly placed were moved to their rightful columns.

## 4.0 Answering The Questions 
Visualiztionof the data for better insight were used.

### 4.1 Which Industry received the highest funding?
![image](https://user-images.githubusercontent.com/120388341/213874452-b6f12159-dd64-4261-b494-0d0c5915dbb9.png)

From the graph, FinTech topped as the Industry that received the highest startup funding

### 4.2 Is there a relationship between the Age of Company and Amount of funding sourced? 
![image](https://user-images.githubusercontent.com/120388341/213874508-b1ec2fa6-6197-4d09-abf8-37ba056de49c.png)

Companies founded in the year 2015 received more funding followed by 2020. It also decreased in 2021. Search Investor behaviour could be based on the type of industry the startup found themselves but not necesarily their age.

### 4.3 Which investors give the highest funding? 
![image](https://user-images.githubusercontent.com/120388341/213874682-59117c03-cb51-4e04-bae9-79fd34474cc4.png)

Inflection point ventures is a leading investor in startups in India the graph.

### 4.4 Is location a factor in sourcing funding?
![image](https://user-images.githubusercontent.com/120388341/213874703-ad7d0da3-3572-4f5d-b59e-eae18878ea8f.png)

It is very obvious that the location of a startup in India places a vital role in the amount a startup receives and the number of investors willing to fund in the startup. Investors prefer to fund startups in Bangalore followed by Mumbai.

### 4.5 Which type of funding is mostly accessed? 
![image](https://user-images.githubusercontent.com/120388341/213874720-184b5d42-a92c-40c9-9b70-db35a0a09933.png)

Startups most often accessed seed funds followed by Series A funds as shown by the graph

### 4.6 Which sector attracts more investors?
![image](https://user-images.githubusercontent.com/120388341/213874733-06e844d6-a769-4d63-9e59-288b9df45958.png)

Investors are mostly attracted to funding the FinTech industry which is the financial sector whiles EdTech which is the educational sector follow second.

##5.0 Conclusion and Recommendation 
The final part deals with the findings and recommendations for future decision making

###5.1 Conclusion 
From our findings, we accept the Alternative Hypothesis. FinTech received the highest sourced amount followed by EdTech

###5.2 Recommendation 
Based on the analysis done on the Indian startup funding, it very pruduent for a startup should consider the FinTech, EdTech and Retail sectors and also should Bangalore, Mumbai and Gurugram and location for their business.
