# Milk-spectra-analysis

This repository contains R code and solutions for the assignment based on the Milk Spectra dataset (Milk_MIR_Traits_data_2023.csv). The assignment involves exploratory data analysis, clustering, principal components analysis, and predictive modeling using principal components regression (PCR). The goal is to gain insights into the milk samples' characteristics and predict the β Lactoglobulin B trait based on mid-infrared (MIR) spectral data.

The initial columns in the dataset contain details (i.e. covariates) of the cows which produced the milk samples and the protein and technological traits of the milk samples measured in the laboratory. The data in the final 531 columns are the MIR spectra, with the first row of these columns detailing the wavenumber (measured in cm−1). The spectral values in the dataset are the absorbance values (the log10 of the reciprocal of the transmittance value). The water region has been removed.

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

