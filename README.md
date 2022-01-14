# Bioinformatics-Drug-Discovery


* Collecting the data(from the ChEMBL database) and preprocessing for SARS coronavirus 3C-like
proteinase.
* Exploratory analysis(chemical space analysis in this case) via the Lipinski descriptors to evaluate the druglikeness of a compound.
* Calculated bioactivity fingerprint descriptors from the PaDEL descriptor and stored them in a data frame for further model building.
* Regression model building with random forest, scatter plot between experimental and predicted pIC50 values.
* Comparison of several machine learning models using lazypredict, visualisation and deployment(currently under process).