This repository reproduces the experiments reported in the PDF, comparing XGBoost, Random Forest, TabNet, and FT-Transformer on multiple tabular datasets.

##Setup

Download the entire "DSS5104_Assignment_2_Submission" Folder. 

requirements.txt is provided in the folder.

##Datasets 

Datasets required are included in the folder. Unzip the "data" folder

#Running the experiments

Each Jupyter notebook labeled 'Adult Income_full_pipeline', 'California Housing_full_pipeline' and 'Porto Seguro Safe Driver_full_pipeline' contains the full pipeline (data loading, preprocessing, hyperparameter tuning, model training, model evaluation).

Open each notebook individual and run all cells from top to bottom. Results of each run will be outputted to the 'results' folder as a CSV file.

#Result analysis

Visualization of results as well as Computation of derived metrics such as the coefficient of variation are done using the "Results_Analysis" Jupyter notebook.

Open the "Results_Analysis" notebook and run all cells.

##Reproducibility

All experiments use fixed random seeds. Running the notebooks will regenerate all reported results.