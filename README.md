# Video-Game-Sales-Predictions
Building a machine learning model to predict success of videogames
The data for this project can be found here on kaggle: https://www.kaggle.com/ignacioch/predicting-vg-hits-1-million-sales-with-lr-rfc/data?scriptVersionId=0

VG_sales.csv is the unmodified data
VG_sales_cleaned.csv is the data with nulls and nonsense values removed
VG_sales_engineered.csv is the data after feature engineering

VG_SalesPrep.ipynb is my code for cleaning the data
VG_SalesPrep2.ipynb contains code for feature engineering
XGBR_Mod.ipynb contains code for creating the machine learning model
VG_Balancing.ipynb contains code for converting the training to a uniform distribution through calculated oversampling. This did not improve model performance and ultimately wasn't used but feel free to look.

XGBR_model is the final pickled model

A slide show presentation is available here https://docs.google.com/presentation/d/1-L40XH05JA4VPnD3mzNZY_1y6Je7zHUd7ME3qPrGQPw/edit?usp=sharing