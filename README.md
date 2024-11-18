

## Project Overview
This repository contains the code, data, and documentation for a research project that investigates the application of machine learning (ML), deep learning (DL), and mathematical modelling to predict tumour progression and treatment responses. The study focuses on the use of unconjugated and conjugated magnetic nanoparticles (mNP-FDG) in comparison to saline solutions for treating cancerous tumours in mice. The results hold significant potential for future applications in in vivo research and cancer treatments.
![Picture 1](https://github.com/user-attachments/assets/c437d375-8024-494e-a045-d03c20578eb8)

## Table of Contents
-[Project Description](#Project-Description)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Pre-processing](#data-cleaning-and-pre-processing)
- [Analysis](#analysis)
- [Findings](#Findings)
- [Limitations](#limitations)
- [Future Directions](#Future-Directions)
- [References](#references)



## Project Description
This project uses AI to help understand how tumours grow and respond to therapies. We used different methods like Machine Learning(ML), Deep Learning(DL) and Mathematical models to validate and predict tumour growth and the effects of treatments.

This study focuses on comparing the effects of saline (as a control), unconjugated iron oxide magnetic nanoparticles (mNP), and conjugated iron oxide magnetic nanoparticles (mNP-FDG) treatments to see how effective they are for reducing tumor size. The main goal is to create models that predict tumor changes more accurately and to offer an interactive GUI tool for predicting tumour volumes based on treatment and time.

The **Tumour Prediction GUI** allows users to input parameters like treatment type, time (in days), and species (currently supporting only mice), and receive a prediction for tumor volume based on the trained models.

<img width="485" alt="Tumour Prediction GUI" src="https://github.com/user-attachments/assets/b9a25649-a5d7-421d-b85a-71b8245d6e32">


## Data Sources
The primary dataset used in this analysis is derived from various studies on tumour dynamics, including unpublished literature related to mNP, mNP-FDG and existing saline treatment datasets.

## Tools
This used the following tools to analyse the data:
- **Grabit (MATLAB)**: For extracting data from graphs
- **Python**: Main programming language for data analysis.
- **Libraries**:
  - **Pandas**: For data manipulation and analysis.
  - **Scikit-learn**: For implementing machine learning algorithms.
  - **Keras/TensorFlow**: For deep learning model development.
  - **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For running and documenting code.

## Data Cleaning and Pre-processing
The following steps were taken to prepare the data:
1. Data Collection: We gathered tumour growth data from various studies.
2. Proved there were no Missing Data or outliers.
3. Data Formatting: Ensured the data was in the right format for analysis.
4. Feature Engineering: Created new features like tumour growth rate and treatment intervals for better predictions.


## Analysis 
The analysis was carried out in several steps:

1. Exploratory Data Analysis (EDA): We first explored the dataset to understand its structure and relationships.
2. Model Development: We built models using ML techniques such as:
    - Decision Trees (DT)
    - Random Forests (RF)
    - Multilinear Regression (MLR)
    - Adaptive Neural Networks (ANN) for deep learning.
3. Mathematical Modelling: We used Logistic Growth and Exponential Decay equations to model tumour changes and predict shrinkage under different treatments.

## Findings
The key findings of the project include:

- Tumour Shrinkage: mNP-FDG were more effective in shrinking tumours compared to saline treatments. The model predicted that the tumours would disappear in about 13.6 days when treated with mNPs.

- Model Accuracy: The ANN model gave the most accurate results when predicting tumour growth compared to other machine learning methods.

- ML,DL and Mathematical models for Cancer Treatment: The models showed that different algorithms can be very helpful in predicting tumour behaviour and improving cancer treatment options.

***Tumour shrinkage when  Untreated***
<img width="991" alt="Screenshot 2024-09-22 at 22 37 03" src="https://github.com/user-attachments/assets/ac0c0a9d-4195-47c6-908f-c6099235ff4c">

***Tumour shrinkage under mNP treatment***
<img width="1022" alt="Tumor shrinkage under Mnps" src="https://github.com/user-attachments/assets/ecc699ff-5c1f-4909-b4f0-1434a6fc33b8">

***Tumour shrinkage under mNP-FDG treatment***
<img width="980" alt="fig 7a" src="https://github.com/user-attachments/assets/a01433d7-e7a1-4aed-ab9c-6a0186cc4de7">


## Limitations
Dataset Size: The relatively small size of the dataset limits the generalisability of the findings across different tumour types and treatments.

Data Homogeneity: Lack of human clinical data, requiring reliance on animal models.
## Future Directions

- SIMBIO Conference: The models will be tested further with new data for the SIMBIO-M 2024 conference paper to make sure they work well with different types of data.
- Future research could explore alternative machine learning algorithms to enhance predictive accuracy.
- Additional studies should consider larger and more diverse datasets to validate findings across different cancer types and treatments.
- Integrating more complex biological models may further improve understanding of tumor responses.
- Tumour Spread: In future, we’ll model how cancer spreads within the body using more advanced mathematical equations.
  
## References
1. Chattopadhyay et al. (2024). [Predicting Tumor Progression](https://arxiv.org/abs/2407.19277)
2. Clarke & Fisher (2020). [Executable Cancer Models](https://doi.org/10.1038/s41568-020-0258-x)
3. Kofi Nti et al. (2021). [Performance of ML Algorithms](https://doi.org/10.5815/ijitcs.2021.06.05)
4. Gao et al. (2015). [Anti-Glioma Effects](https://doi.org/10.1166/jbn.2015.2076)
5. Qi et al. (2022). [Metabolic Analysis of Anticancer Effects](https://doi.org/10.3390/biomedicines10030528)
