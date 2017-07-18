# BioinformaticsWithMachineLearning
Finding Missing Protein Protein Interactions for Asthma and Allergy Dataset using Machine Learning Algorithms

## Installation and Running
* Download the Repository from Github (clone or download as zip)
* To run Jupyter Notebook files, (ones with .ipynb extentions), you need to install Anaconda on:
> https://www.continuum.io/downloads
> Preferably Python 2.7 version
* Run Jupyter Notebook when Anaconda is done installing and open the file location with this project
* You can now open and run the python code in the notebooks

## Components of Project
1. Reading and Understanding the Dataset
> This is just taking a peek into the properties of Asthma and allergy dataset
2. Data Processing
> This is where we create a complimentary set of NonPPIs and make values of datasets numeric for the ML algorithms to comprehend them as features
3. Finding Missing PPIs using ML Algorithms
> We deep-dive into the various ML algorithms and compare their perfomance. We choose a candidate model and use it to predict Missing PPIs 
4. Comparing Results with that of Hybrid Model
> Here, we compare the results we get from ML to the previous results that we obtained from the Hybrid Model (Hub Enrichment & Diffusion Kernel). We make conclusions as to the relevance of our findings to the hypothesis that Machine Learning can be used to predict missing PPIs similar to the ones predicted using Hybrid Model technique

## Takeaway
If we had a dataset with several features, we could perform preprocessing of the data, feature reduction and principal component analysis, to make our model highly accurate and therefore make optimal predictions.
