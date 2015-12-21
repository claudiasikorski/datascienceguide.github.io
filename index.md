scikit
R
weka


# How Do I Start Learning Data Science?

This is a hands on or applied guide to getting started with *data science*.  It begins with what exactly is data science, and how to get the required background and later goes into details of learning and practicing the different multifacted streams of data science.

## Why create this guide

 Ever since Harvard Business Review claimed that being a [Data Scientist is the Sexiest Job of the 21st Century](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century/) there have been countless guides, blogs, courses, new sites and tutorials on different aspects of data science, machine learning, statistics and many many more related topics.  Different than other guides, this site strives to act as (somewhat comprehensive) learning plan or a road map with practical advice for getting started on a journey into the world of data science.  While books are great (and are recommended), a large reading lists are daunting and are not conductive to becoming a better data scientist, rather the way to get better is to learn a little, play a little, present results a little, get feedback a little, rinse and repeat!  And this guide provides such a framework by explaining topics, providing sample code and data and links to revelant resources along the way!

## About this guide

This originally was written by Andrew Andrade and Professor Golab as suplimental notes for MSCI 723, a graduate management sciences course on data science and big data.  Since the students come from many different backgrounds (some non-technical) we strived to provide many optional background readings (both for beginners and advanced people) which we think will be useful.  We start of with data science with small to medium data, and later touch on big data. (First learn how to analysis data, then learn how to deal with big data)

While we attempt to be comprehensive, this guide is still a work in progress and we look foward to edits, improvements and suggetions.  Please feel free to send us a pull request (TODO: how to do a pull request)

# What is data science?

 - data analyist from SF
 - knows more programming than a statstician, knows more stats than a programner
 - About causility and actional insights!

## Good old venn diagram!

## What is big data?

- How big is big?

- Small data "Medium Data" vs big data

## Data engineering vs Data science?

### Hadoop monkey, ETL drone

## What types of jobs are out there?


# Required background

## Precalc Mathematical Thinking

https://www.khanacademy.org/math/precalculus
https://www.coursera.org/course/maththink
https://www.coursera.org/course/intrologic

betterexplained.com


## Linear Algebra

From: https://www.quora.com/What-concepts-of-linear-algebra-should-one-master-to-be-a-good-data-scientist

For Machine Learning: A lot of ML concepts are tied to linear algebra concepts. Some basic examples, PCA - eigenvalue, regression - matrix multiplication... As most ML techniques deal with high dimensional data, they are often times represented as matrices. 


Singular value decomposition, projections, principal components, eigenvalue, eigenvectors, regression, matrix multiplication, matrix operations, matrix, inverse, solving differential equations using matrices.

For Mathematical Modeling: for example, if you want to capture behaviors (sales, engagement, etc.) in a mathematical model, you can use matrix to breakdown the samples into their own subgroups, and each has its own parameter instead of using a global value. This requires some basic matrix manipulation. Matrix inversion, derivation, solving partial differential or first order differential equations with matrices, for example. 
For Understanding High Dimensional Distribution: multinomial as the basic example and there are many more.

http://matrixcookbook.com
https://www.khanacademy.org/math/linear-algebra

Linear Algebra Done Right, Axler

Hands on:

http://alexhwoods.com/2015/07/11/linear-algebra-for-data-scientists/

## Calculus

https://www.khanacademy.org/math/calculus
https://www.khanacademy.org/math/integral-calculus
https://www.khanacademy.org/math/multivariable-calculus
https://www.khanacademy.org/math/differential-equations

## Statistics

### Discriptive Statistics

mean, median, range, standard deviation, variance, Histograms box plots

Probability Theory

Bayes vs Frequentist

Bayes Theorem

Random variables

Distribution functions (normal, poisoon, gaussian)

Percentiles and Outliers

Skewness

Analysis of Variance

Prof Desnsity Function

Central Limit theorem

Monte carlo

Hypothesis testing

p-value

chi^2

estimation

confidence interval

maximum-likelihood estimation

Kernel density estimate

regression

co-variance

corellation

pearson coeff

causation

least squares


# Distance measurements

euclidean distance

Markov Chains 


MCMC



## Data and Programming Fundamentals

### Programming fundamentals

- arrays, loops, etc.

### Databases
Relational algebra and DB basics

## Data types:

### Tabular data

spreadsheet, csvs, dataframes, data series

### JSON, XML

### NoSQL

SQL joins 
http://blog.codinghorror.com/a-visual-explanation-of-sql-joins/


### MISC Topics

REGEX!

Super userful to extract information, data cleaning!

CAP theorem
http://www.julianbrowne.com/article/viewer/brewers-cap-theorem

Information Entropy
https://www.khanacademy.org/computing/computer-science/informationtheory/moderninfotheory/v/information-entropy

## Multi dimensional data

- DataSharding

- OLAP

- ETL

## Business Analytics vs Business Intelligence

https://www.quora.com/What-is-the-difference-between-business-intelligence-and-business-analytics-1

https://rapidminer.com/summarizing-differences-business-intelligence-advanced-analytics/

Tools and Environment Setup!

### Data structures and algorithms:

- hash functions, binary tree, algorithm complexity, big O notation

### Numerical methods

## Running Servers and Virtual Machines

Commandline, linux


# Exploratory data analysis

## Summary statistics

## Visualization

ggplot
Rshiny
D3.js


# Data Tools

- Many tools exist.  We start with excel since it is the most basic for dealing with tabular data, later we focus on open source tools: first with workbenches/ interfaces and then programming frameworks.

## Why open source?

- view source code, contribute, free innovation, cross platform, not tied down

## Excel/ Open Office

# Java Work Benches

Java-based environments, workbenches and graphical user interfaces (GUIs) that can be used for data science.  From the [original article](http://machinelearningmastery.com/java-machine-learning/) outlining more details.

## [Weka](http://www.cs.waikato.ac.nz/ml/weka/)

Waikato Environment for Knowledge Analysis (Weka) is a data mining platform created by the University of Waikato, New Zealand. It  provides a graphical user interface, command line interface and Java API. It is perhaps the most popular Java machine learning library and a great place to start or practice machine learning.

Recommended for beginners, great out of the box visualizations

## KIME

Konstanz Information Miner

## RapidMiner

## ELKI

Environment for DeveLoping KDD-Applications Supported by Index-Structures (ELKI) 


# Programming Frame works

## Why write code?
- reproducable
- scales better
- easily distributed

# Java Libraries

## Java-ML

## JSAT

# Python Libraries

## ScitKit learn

## Xgboost

## Orange


## R

R Studio
Rattle (http://rattle.togaware.com/)
(that other R IDE)

# Big data tools

## Hadoop
 
## Hive
SQL on clusters

## Map reduce

Pig


Spark

Storm

Flume, Scribe, Chukwa

http://flume.apache.org/


Apache Nutch, Talend, Scraperwiki

Wbscraper, Sqoop








