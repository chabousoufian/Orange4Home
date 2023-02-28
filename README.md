# Orange4Home dataset Overview

This project involved the following steps:

1. Extraction of tables from a MySQL database
2. Merging and pre-processing of data to create a dataset containing 256 sensors (256 features)
3. Implementation of three different approaches to model creation:
    A. **All-feature selection:** using the entire dataset to create MLP, LSTM, and GRU models.
    
    B. **Feature selection:** using F-ANOVA to select the 50, 100, 150, and 200 most relevant parameters, and creating models based on these selected features.
    
    C. **Principal Component Analysis (PCA):** creating models using PCA-MLP, PCA-LSTM, and PCA-GRU with 50, 100, 150, and 200 principal components.

Visualization of project architecture in the following diagram:

![the architecture of the project](https://github.com/chabousoufian/Orange4Home/blob/master/Picture.jpg?raw=true")