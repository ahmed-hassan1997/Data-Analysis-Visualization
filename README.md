# Data-Visualization
in this project we  will  explore data analysis on a dataset . You will use Python data science and data visualization libraries like (pandas-matplotlib-seaborn)-to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships

## overview

this project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. Select one or two major paths in your exploration, choose relevant visualizations along that path, and then polish them to construct a story for your readers to understand what you found.

---

### Table of Contents


- [Choose your Dataset](#Choose-your-Dataset)
- [ask-question-to-analyze-data](#ask-question-to-analyze-data)
- [Explore Your Data](#Explore-Your-Data)
- [Visualize-data](#Visualize-data)
- [Document your Story](#Document-your-Story)
- [Create your Slide Deck](#Create-your-Slide-Deck)
- [end](#end)

---


## Choose Your Data Set :point_left:

###### loan data

Click this link [dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.

###### link Loan Data from Prosper [click](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) 

---

## Explore Your Data
 ### explore null value in column
 <p width = "1000px">
<img src = "./image/null_value in column.png">
</p>

---
## ask-question-to-analyze-data

### what is the highest categories in CreditGrade column ?

###### solution : this graph show this

<img src="./image/f1.png" alt="drawing" style="width:1000px;"/>

### what is the highest categories in ProsperRating(alpha) column ?

###### solution : this graph show this

<img src="./image/f2.png" alt="drawing" style="width:1000px;"/>

### What is the percentage of the people who make the papers of the loan? 

###### solution : this graph show this

<img src="./image/f3.png" alt="drawing" style="width:1000px;"/>


### What is the state of people which take loan ? 

###### solution : this graph show this

<img src="./image/f4.png" alt="drawing" style="width:1000px;"/>

### What is the relation between CurrentCreditLines && OpenCreditLines ? 

###### solution : this graph show this

* relation between column is linear relation and this is positive correlation

<img src="./image/f5.png" alt="drawing" style="width:1000px;"/>


### What is the relation between EmploymentStatusDuration && EmploymentStatus ? 

###### solution : this graph show this

* notice that 75% under 100 duration

<img src="./image/f6.png" alt="drawing" style="width:1000px;"/>

### What is the violinplot between CreditGrade && BorrowerRate ? 

###### solution : this graph show this

* 50% or greater in (E,HR) is above 0.35 from Borrow rate

<img src="./image/f7.png" alt="drawing" style="width:1000px;"/>


### What is the correlation between the three column [EstimatedLoss , EstimatedReturn , ProsperRating (numeric)] ? 

###### solution : 

* high positive correlation between [EstimatedReturn ,EstimatedLoss ]
* high negative correlation is between [EstimatedLoss , ProsperRating (numeric)]

<img src="./image/f9.png" alt="drawing" style="width:1000px;"/>


### What is the correlation between the three column ['MonthlyLoanPayment', 'TotalTrades','LenderYield'] ? 

###### solution : 

###### correlation between the three column is very high 
<img src="./image/f10.png" alt="drawing" style="width:1000px;"/>

---

### explore correlation  between column
 <p width = "1000px">
<img src="./image/corr.png" alt="drawing" style="width:1000px;"/>
</p>
---
## end :raising_hand:

