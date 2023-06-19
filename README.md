# Metabolomic Analysis in Pediatric Crohn's Disease Patients: A Machine Learning Approach

This repository contains the code and data for the research project titled "Metabolomic Analysis in Pediatric Crohn's Disease Patients: A Machine Learning Approach".

## Authors


- Santiago Miro Trejo
  - University of Alberta
  - Email: mirotrej@ualberta.ca


- Ricardo Suarez Suarez
  - University of Alberta
  - Email: suarez@ualberta.ca

- Namitha Guruprasad
  - University of Alberta
  - Email: ngurupra@ualberta.ca

- Ganesh Tata
  - University of Alberta
  - Email: gtata@ualberta.ca


- Nabil Al Asmer
  - University of Alberta
  - Email: alasmer@ualberta.ca

## Abstract

Inflammatory Bowel Diseases (IBD) are disorders in the intestinal tract with no permanent cure and can often lead to hospitalizations, surgeries, and life-threatening complications. Furthermore, IBD is more severe in children than in adults and carries a risk of growth failure, delayed puberty, depression, anxiety, and cancer.

Metabolomics allows for the analysis of the metabolic changes in gut microbial metabolism by identifying and quantifying the compounds in biological samples. Therefore, metabolomics provides a unique opportunity to associate pediatric Crohn's disease (pCD) with an altered multivariate metabolite profile.

The objective of this work is to perform an exploratory data analysis on serum metabolomics from 56 pCD patients. Samples were collected twice: once at study initiation (Visit One) and again for completion (Visit Four). The collected serum underwent liquid chromatography followed by mass spectrometry to identify 131 compounds.

Serum metabolites are analyzed using Unsupervised (U.ML) and Supervised (S.ML) Machine Learning algorithms. U.ML is used to reduce the dimensionality of the data and identify clusters, while S.ML is used to develop regression and classification algorithms to assess the correlation between metabolites and disease activity.

Results show that Tryptophan is the metabolite that ranks the highest in feature importance scoring. Histidine is another metabolite that correlates well with the severity of the disease. In the regression analysis, it was observed that Partial Least Squares (PLS) with LOL reduction setting incurred the least Mean Squared Error (MSE) of 0.8806. In the classification process, Random Forest with Linear Discriminant Analysis (LDA) setting achieved the least False Negative rate of 0.53, and K-Nearest Neighbors (KNN) with Principal Component Analysis (PCA) setting yielded the highest accuracy score of 63.

In conclusion, we infer that the above alternatives did not have any exceptional impact on our findings. The major reason for this might be the scarcity of data and the imbalance or underrepresentation of some data labels.

To read the complete paper: 
