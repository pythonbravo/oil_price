# A Tour of the Oil Industry

## Machine Learning to predict share prices in the Oil & Gas Industry

In a nutshell, this is a quick introduction **to understand the potential of data science and machine learning used in the oil industry**. I have chosen to work with the stock price of a few oil companies (or oil service company) and the oil price dataset as an example. Just to be clear, the intention is *not* to provide an analysis of the current situation in the oil industry. The main objectives here are to show the potential and **give you the tools to create your own view** of the markets and apply it to other problems or even industries.

In the low price world, reducing costs, saving time and improving safety are crucial outcomes that can be benefited from using machine learning in oil and gas operations. Find below a quick list with a few of the applications of data analysis and machine learning in the Oil & Gas upstream industry:

* Optimization of valve settings in smart wells to maximize NPV.
* Machine Learning based rock type classification
* Big data analysis on wells downtime.
* Data-driven production monitoring.
* Identifications of patterns using multiple variables during exploration phase.
* Reservoir modelling and history matching using the power of pattern recognition.
* Drilling rig automation.
* Additional opportunities where gather large volumes of information in real-time or by using multiple analogs.
* Deep learning to improve the efficiency and safety of hydraulic fracturing.
* Provide more intelligence at the wellhead.
* Integrated asset modeling optimization using machine-learning based proxy models.

I have tailored a quick exercise on how to use artificial intelligence using oil price and share price of a few companies. The notebook will focus on loading data and doing some illustrative data visualisations along the way. I will then use linear regression, cluster analysis and Random Forest to create a model predicting the share price in the short term.

I have been using data analysis and machine learning in different tasks in my current and previous jobs as a Reservoir Engineer. **Excel is the most common tool** for any type of analysis in the industry. However, it is certainly limited to basic data analysis, manipulation and to construct predictive models. We understand this conservative industry is sometimes a bit reluctant or delayed implementing modern analysis and predictive workflows to drive decisions. Also, due to the lack of investment in "lower for longer" oil prices and not many young engineers joining us, we are behind in the race implementing these techniques.

Firstly, lets start with what the list of tools required. The modern world of data science offers multiple ways of analyzing and predicting patterns. **Python is the programming language used for this exercise**. I personally use it under the umbrella of the **Anaconda distribution**. I will also be hoping to learn a lot from this exercise, so feedback is very welcome.

The main libraries that we will use are:

* *Numpy*: Library for multidimensional arrays with high level mathematical functions to operate them
* *Pandas*: Works on top of Numpy, offer a great way of manipulate and analyse data.
* *Matblotlib*: Plotting and visualization.
* *Seaborn*: Works on top of matplotlib to provide a high level interface for attractive plotting and visualization.
* *Scikit Learn*: Libraries for Machine Learning. In this exercise we will use the following: Linear Regression, Random Forest Regression and K-means

For the purposes of this interactive quick guide, I will use these sets of data:

* Oil price dataset from the U.S Energy Information administration.
* Share price dataset from Yahoo Finance in a daily frequency from the following companies:

> Shell (RDSB.L)

> BP (BP.L)

> Cairn Energy (CNE.L)

> Premier Oil (PMO.L)

> Statoil (STL.OL)

> TOTAL (FP.PA)

> ENGIE (ENGI.PA)

> Schlumberger (SLB.PA)

> REPSOL (REP.MC)

There are three parts that my workflow will cover:

1. Loading data and introduction to feature engineering

2. Data Analysis

3. Machine Learning and Prediction!

I will skip sections of the code below to keep the article in a reasonable size. If you want to see the entire code with explanations, I have created the following notebook.

## Lets start coding!
