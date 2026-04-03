# Adult Income Gender Clustering

This project explores the latent socio-economic structure of the Adult Income dataset using a gender-stratified unsupervised learning approach.

The analysis compares **K-Means** and **Gaussian Mixture Models (GMM)** on the male and female subsets of the dataset, with the aim of identifying interpretable socio-economic profiles beyond direct income prediction.

## Project Aim

The project investigates:

- whether distinct socio-economic clusters exist in the Adult Income dataset
- whether **GMM** provides more informative clustering solutions than **K-Means**
- whether the latent socio-economic structure differs across **male** and **female** subsets

## Methods

The main methods used in this project are:

- **K-Means clustering**
- **Gaussian Mixture Models (GMM)**
- **Silhouette score** as a supplementary clustering check
- **PCA** for 2-D visualisation
- **3-D cluster visualisation** using selected interpretable variables

## Main Findings

The results suggest that:

- the dataset contains **interpretable socio-economic clusters** rather than random groupings
- **GMM** provides more informative and interpretable solutions than K-Means for this dataset
- the **male** and **female** subsets do not share the same latent socio-economic structure
- even when `income` is excluded during training, the selected GMM solutions still reveal a clear gender difference in high-income concentration

Overall, the project shows that unsupervised clustering can be used to explore hidden socio-economic stratification in demographic data.

## Repository Structure

```text
adult-income-gender-clustering/
├── adult_income_gender_clustering_report.pdf
├── adult_income_gender_clustering_code.pdf
└── README.md
