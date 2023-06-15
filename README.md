# Data-Analitycs-for-Smart-Agriculture Project 2022-2023
## ReCrop

![image](https://github.com/giusti-leo/Data-Analitycs-for-Smart-Agriculture/assets/61985313/d77e5bc8-3599-446d-9e5f-c99dc64e3e7c)

The goal of the project is to design and propose a Smart Agriculture solution in Agriculture 4.0, from Idea Proposal and Data Collection to Data Analysis and Economic Impact Evaluation. <br />
In order to overcome climate changes and uncertainty on resourse availability issues, ReCrop solution is a crop recommendations based on environmental data and a estimated economic revenue for suggested crops. <br />
<br />
In the development of the project we used Classification, Clustering and Regression techniques.
<br />
We applied Supervised techniques in order to classify the best crop given certain environmental conditions. After the analysis we notice strange accuracy results and an careful data exploration led us consider the first dataset as unreal.
* Logistic Regression without an hyperparameter tuning with an accuracy value of 93%
* Decision Trees with an accuracy value of 96% 
<br />
On the second dataset we applied Unsupervised techninques:
* Clustering with PCA or without PCA ( using Elbow Method, Agglomerative Clustering and K-Means) and comparison
<br />
On the singular crop data inside the same cluster, we applied Regression techninques in order to predict the estimated economic revenue for each crop:
* Linear Regression
* Least Squared Regression
<br />
Economic revenue results were not reliable due to data problems. 

### Steps
* Idea proposal
* Dataset Collection
* Data Pre-processing and Cleaning
* Data Exploration before Classification
* Classification models
* Data Exploration before Clustering
* Clusteting models
* Data Exploration before Regression
* Regression models
* Presentation

### Built With

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)

#### Group Members:
Leonardo Giusti
<br />
Luca Giudici
<br />
Daniele Giorgianni
<br />
