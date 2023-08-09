# Milk-spectra-analysis

Understanding the complex relationship between milk composition, MIR spectral data, and protein traits has significant implications for industries such as dairy production and quality control. The insights gained from this analysis can aid in optimizing processes, enhancing product quality, and contributing to advancements in dairy technology. This repository contains R code and solutions for the assignment based on the Milk Spectra dataset (Milk_MIR_Traits_data_2023.csv). The assignment involves exploratory data analysis, clustering, principal components analysis, and predictive modeling using principal components regression (PCR). The goal is to gain insights into the milk samples' characteristics and predict the β Lactoglobulin B trait based on mid-infrared (MIR) spectral data.

**Dataset Description:**

The Milk Spectra dataset comprises mid-infrared (MIR) spectral data extracted from milk samples, alongside associated protein and technological traits. The dataset presents a unique opportunity to delve into the intricate relationships between milk composition and spectral patterns, shedding light on important traits like the β Lactoglobulin B protein.The initial columns in the dataset contain details (i.e. covariates) of the cows which produced the milk samples and the protein and technological traits of the milk samples measured in the laboratory. The data in the final 531 columns are the MIR spectra, with the first row of these columns detailing the wavenumber (measured in cm−1). The spectral values in the dataset are the absorbance values (the log10 of the reciprocal of the transmittance value). The water region has been removed.

**Assignment Tasks**
1. Load and preprocess the dataset, including random deletion of an observation.
2. Visualize MIR spectra and β Lactoglobulin B trait, removing outliers.
3. Apply hierarchical and k-means clustering to identify clustering structures.
4. Perform principal components analysis (PCA) and determine the required number of components.
5. Derive and analyze principal component scores for milk samples.
6. Research and provide a synopsis of Principal Components Regression (PCR) method.
7. Use PCR to predict β Lactoglobulin B levels from MIR spectra for a test set.
8. Impute missing β Lactoglobulin B values using matrix completion (PCA).
9. Predict β Lactoglobulin B values using PCR for different scenarios and analyze the results.
    
**Project Objectives**
1. Exploratory Data Analysis: Uncover patterns, trends, and outliers in the milk spectra dataset.
2. Clustering Analysis: Identify potential clusters within the MIR spectral data.
3. Principal Components Analysis (PCA): Reduce dimensionality and gain insights into the most influential components.
4. Principal Components Regression (PCR): Develop a predictive model for the β Lactoglobulin B trait using PCR.
5. Imputation and Comparison: Explore strategies to handle missing values and evaluate their impact on prediction.



