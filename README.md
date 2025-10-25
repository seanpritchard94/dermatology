# Overview #

## Project Info ##

- Developed by: Sean Pritchard
- for: CSCA 5632: Unsupervised Algorithms in Machine Learning Final Project
- URL: https://github.com/seanpritchard94/dermatology
- Data Source: https://archive.ics.uci.edu/dataset/33/dermatology
- Python version: 3.13

## Data Collection and Provenance ##

This data was originally collected by Nilsel Ilter, M.D., Ph.D., Gazi University, School of Medicine, Ankara, Turkey and H. Altay Guvenir, PhD., Bilkent University, Department of Computer Engineering and Information Science, Ankara, Turkey.

The data collection procedure is described as:
> "Patients were first evaluated clinically with 12 features. Afterwards, skin samples were taken for the evaluation of 22 histopathological features. The values of the histopathological features are determined by an analysis of the samples under a microscope
> In the dataset constructed for this domain, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible,and 1, 2 indicate the relative intermediate values." (Ilter, N. & Guvenir, H., 1998)

## Unsupervised Learning Problem Description ##

This project will use unsupervised machine learning techniques including KMeans, Agglomerative Clustering to cluster the data samples. The results of clustering will then be compared to the labels to determine accuracy. Additionally, supervised machine learning techniques will be used and results will be compared with the unsupervised clustering.

The researchers who collected the data describe the challenge of differential diagnosis of erythemato-squamous as follows:

> The differential diagnosis of erythemato-squamous diseases is a real problem in dermatology. They all share the clinical features of erythema and scaling, with very little differences. The diseases in this group are psoriasis, seboreic dermatitis, lichen planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris. Usually a biopsy is necessary for the diagnosis but unfortunately these diseases share many histopathological features as well. Another difficulty for the differential diagnosis is that a disease may show the features of another disease at the beginning stage and may have the characteristic features at the following stages. (Ilter, N. & Guvenir, H., 1998)

Because of the challenges in performing differential diagnosis, a machine learning model that can accurately assist in this task would be valuable to dermatologists.

**Type of Learning and Task:** This is a **multiclass classification** machine learning problem. I will evaluate **unsupervised clustering algorithms** including KMeans, Agglomerative Clustering and **supervised learning algorithms** including Random Forest to determine which performs best with this dataset.

**Project Goal:** Determine the effectiveness of various machine learning algorithms and identify the best machine learning algorithm for accurately identifying the underlying disease when a patient presents with erythemato-squamous symptoms.

# Citations #

- Ilter, N. & Guvenir, H. (1998). Dermatology [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5FK5P.
- GeeksforGeeks. (2025, July 23). Implementing PCA in python with scikit-learn. https://www.geeksforgeeks.org/machine-learning/implementing-pca-in-python-with-scikit-learn/
- Uzila, A. (2025, January 20). K-means clustering and principal component analysis in 10 minutes. Towards Data Science. https://towardsdatascience.com/k-means-clustering-and-principal-component-analysis-in-10-minutes-2c5b69c36b6b/
