### Analyzing Thanksgiving Dinner 

In this project, I analyzed data on Thanksgiving dinner in the US. The dataset came from [FiveThirtyEight](http://fivethirtyeight.com/), and can be found [here](https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015).

The dataset is stored in the **thanksgiving.csv** file. It contains **1058** responses to an online survey about what Americans eat for Thanksgiving dinner. Each survey respondent was asked questions about what they typically eat for Thanksgiving, along with some demographic questions, like their gender, income, and location. This dataset helped me discover regional and income-based patterns in what Americans eat for Thanksgiving dinner.

The dataset has **65** columns, and **1058** rows. Most of the column names are questions, and most of the column values are string responses to the questions. Most of the columns are categorical, as a survey respondent had to select one of a few options. For example, one of the first column names is **What is typically the main dish at your Thanksgiving dinner?**. The potential responses are:

- Turkey
- Other (please specify)
- Ham/Pork
- Tofurkey
- Chicken
- Roast beef
- I don't know
- Turducken

Most of the columns follow the same question/response format as the above. There are also quite a few **NaN** values in the columns, which occurred when a survey respondent didn't fill out a question because they didn't want to, or it didn't apply to them.

Here are descriptions of some of the most important columns of the dataset:
- **RespondentID** -- a unique ID of the respondent to the survey.
- **Do you celebrate Thanksgiving?** -- a **Yes**/**No** reponse to the question.
- **How would you describe where you live?** -- responses are **Suburban**, **Urban**, and **Rural**.
- **Age** -- resposes are one of several categories, such as **18-29**, and **30-44**.
- **How much total combined money did all members of your HOUSEHOLD earn last year?** -- one of several categories, such as **\$75,000** to **\$99,999**.

## Getting Started

Download the [Jupyter notebook](https://github.com/arjunchndr/Data-Analysis-with-Pandas-Analyzing-Thanksgiving-Dinner/blob/master/Analyzing%2BThanksgiving%2BDinner.ipynb) if you have all the dependencies listed below. 

## Built With

* [Python 3.6.3](https://www.python.org/downloads/) 
* [Pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) 
* [Jupyter 5.1.0](http://jupyter.org/install.html) 
* [Matplotlib 2.1.0](https://matplotlib.org/2.1.0/index.html)
