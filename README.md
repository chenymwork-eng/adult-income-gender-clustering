# Adult Income: Gender-Stratified Clustering

Exploring socio-economic patterns through unsupervised learning and interpretable visualisation.

## Overview

This analysis compares K-Means and Gaussian Mixture Models (GMM) on male and female subsets of the Adult Income dataset. It asks whether clustering can reveal meaningful socio-economic profiles beyond direct income prediction.

The project demonstrates exploratory data analysis, model comparison and communication of findings—skills relevant to analytics and evidence-based business research.

## Research questions

- What socio-economic profiles emerge within each subset?
- How do K-Means and GMM differ in interpretability?
- How does income concentration vary across the resulting clusters when income is excluded from model training?

## Methods

- K-Means and Gaussian Mixture Models for clustering.
- Silhouette score as a supplementary clustering diagnostic.
- PCA for two-dimensional visualisation.
- Three-dimensional visualisation using interpretable variables.

## Findings reported in the analysis

The analysis identifies interpretable socio-economic clusters and reports that the selected GMM solutions are more informative than the K-Means alternatives. It also reports differences between the two subsets, including differences in high-income concentration when income is excluded during training.

These findings describe patterns in this dataset. They do not establish causal explanations or justify conclusions about individuals.

## Explore the work

- [View the analysis notebook (PDF)](adult_income_gender_clustering_notebook.pdf)

The available notebook is a PDF document, not an executable notebook.

## Interpretation and limitations

Cluster assignments depend on preprocessing, feature selection and model settings. The male/female comparison follows the categories used in this analysis and does not represent the full range of gender identities. Interpret the results within the dataset's historical and sampling context.
