## Project Overview
This repository contains the code and data associated with my dissertation project, which focuses on predicting tumour dynamics in response to treatments using machine learning (ML), deep learning (DL), and mathematical modelling techniques. The goal is to enhance understanding of tumour progression and improve treatment regimens for cancers, particularly through the use of magnetic nanoparticles (mNP-FDG) and saline solutions.
![Picture 1](https://github.com/user-attachments/assets/c437d375-8024-494e-a045-d03c20578eb8)

## Table of Contents
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Pre-processing](#data-cleaning-and-pre-processing)
- [Analysis](#analysis)
- [Results and Findings](#results-and-findings)
- [Limitations](#limitations)
- [References](#references)
- [Getting Started](#getting-started)

## Data Sources
The primary dataset used in this analysis is derived from various studies on tumour dynamics, including unpublished literature related to mNP-FDG treatments and existing saline treatment datasets.

## Tools
This project utilizes the following tools and libraries:
- **Python**: Main programming language for data analysis.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Keras/TensorFlow**: For deep learning model development.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive code execution and documentation.

## Data Cleaning and Pre-processing
The following steps were taken to prepare the data:
1. **Data Loading and Overview**: Initial exploration of the dataset to understand its structure and content.
2. **Checking/Handling Missing Values**: Identification and resolution of any missing data entries.
3. **Data Formatting**: Standardization and transformation of data.
  
<img width="980" alt="fig 7a" src="https://github.com/user-attachments/assets/a01433d7-e7a1-4aed-ab9c-6a0186cc4de7">

## Analysis
The analysis involves creating a machine learning pipeline to predict tumour dynamics. The pipeline incorporates various algorithms and models to assess treatment effects:
## Findings
Using the developed pipeline, predictions on the unseen dataset revealed that 98.82% of the distribution was predicted as -1, indicating the absence of linear B-cell epitopes. In contrast, only 1.18% were predicted as 1, indicating the presence of linear B-cell epitopes. This result highlights how linear B-cell epitopes are relatively rare in this dataset.

## Conclusions
The use of Principal Component Analysis (PCA) for feature reduction may have led to the loss of important information, potentially impacting the accuracy of predictions.
The complexity of tumor dynamics and individual variability in responses to treatments may not be fully captured by the models used.

## Future Directions

Future research could explore alternative machine learning algorithms to enhance predictive accuracy.
Additional studies should consider larger and more diverse datasets to validate findings across different cancer types and treatments.
Integrating more complex biological models may further improve understanding of tumor responses.

## References
1. Chattopadhyay et al. (2024). [Predicting Tumor Progression](https://arxiv.org/abs/2407.19277)
2. Clarke & Fisher (2020). [Executable Cancer Models](https://doi.org/10.1038/s41568-020-0258-x)
3. Kofi Nti et al. (2021). [Performance of ML Algorithms](https://doi.org/10.5815/ijitcs.2021.06.05)
4. Gao et al. (2015). [Anti-Glioma Effects](https://doi.org/10.1166/jbn.2015.2076)
5. Qi et al. (2022). [Metabolic Analysis of Anticancer Effects](https://doi.org/10.3390/biomedicines10030528)
