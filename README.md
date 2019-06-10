# Instacart_Data_Analysis
Instacart data analysis. Predicting what customers will buy.

This Repo contains following 3 folders:

### IPython_Notebooks	
This folder contains ipython jupyter notebooks.

    1.Instacart-EDA.ipynb-	This notebook primarily does exploratory data analysis and data visualization.

    2.Instacart-feature_engineering and flat file creation.ipynb-	In this notebook The dataframes are merged to obtain order-product-user level details together along with feature engineering. Finally, the data is flattened and exported to a csv which will be later used as training data.

    testdata_flatfile.ipynb- The test dataset in "order_products__test_cap.csv" contains order id and associated products in the order. To predict which product, the test users would currently order, the model would need these test user's previous order histories. The model would need these test users based user features, product features and user-product features.

    3.Instacart-Logistic Regression and Testing.ipynb-Logistic Regression classifier is trained based on the training data and features obtained from "2.Instacart-feature_engineering and flat file creation.ipynb" . Finally, its tested on test data obtained from "testdata_flatfile.ipynb".

### Report and Presentation	
This folder contains following files

        1. Instacart Data Analysis_Presentation.pdf: Presentation containing findings and methodology used in analysing the dataset

        2. Instacart Data Analysis_Report_SanchariChowdhuri.pdf : Report containing details of findings, approach and methodology used tfor feature Engineering and finally training and testing the model
### html_version_of _ipython_notebooks

        These are html version of the ipython notebooks uploaded in folder "Instacart_Data_Analysis/IPython_Notebooks/".


#### Alternatively this repo can be viewd at "https://nbviewer.jupyter.org/github/SanchariChowdhuri/Instacart_Data_Analysis/tree/master/"
