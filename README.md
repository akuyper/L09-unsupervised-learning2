# L04 Unsupervised Learning

Download the repository as a zip folder and begin an R project for this lab. The zip folder will contain instructions (repeated below) and a template to get an Rmd file started.

# Overview

The goal of this lab is to continue practicing the application of unsupervised learning techniques.

# Datasets 

We will be utilizing the `USArrests` data (*USArrests.csv*) which is contained in the **data** subdirectory. Students are able to access the appropriate codebook using `USArrests`. We we also be using the `college_reshaped.csv` dataset which contains both categorical and numerical data (found in **data** subdirectory). The dataset was formed using the `College` dataset from the `ISLR` package.

# Exercises

Please complete the following exercises. The document should be neatly formatted. 

<br>

#### Exercise 1 (Ex. 9 Section 10.7 pg 416)
Consider the `USArrests` data. Perform hierarchical clustering on the states.

a. Using hierarchical clustering with complete linkage and Euclidean distance, cluster the states.

<br>

b. Cut the dendrogram at a height that results in three distinct clusters. Which states belong to which clusters?

<br>

c. Hierarchically cluster the states using complete linkage and Euclidean distance, after scaling the variables to have standard deviation one.

<br>

d. What effect does scaling the variables have on the hierarchical clustering obtained? In your opinion, should the variables be scaled before the inter-observation dissimilarities are computed? Provide a justification for your answer.


<br><br>

#### Exercise 2
Use the `clustMixType` package to perform clustering on the `college_reshaped.csv` dataset. 

<br><br>

#### Exercise 3
Use the `cluster` package (specifically the `daisy()` & `pam()`) to perform clustering on the `college_reshaped.csv` dataset.

