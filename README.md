# Portofolio

**Certificates**
- List of certificates obtained

**Inaugural**
- Dataset used for BM_Wordclouds.ipynb
- Data available [here](https://www.presidency.ucsb.edu/documents/presidential-documents-archive-guidebook/inaugural-addresses).

**BM25_Wordclouds.ipynb**
- Using the inauguration speeches by the US presidents, BM25 is calculated from scratch.
- [BM25](https://en.wikipedia.org/wiki/Okapi_BM25) is a ranking function used by search engines to estimate the relevance of documents to a given search query.
- Words with high BM25 values are visualised with word clouds.

**DemandForecasting.ipynb**
- Demand forecasting models are created and compared. Models considered are:
  - Gradient Boosting Regression
  - LightGBM
  - XGBoost
  - Support Vector Regressor
  - Ridge Regression
  - Lasso Regression
  - Elastic Net
  - RNN (Recurrent Neural Networks)
  - LSTM (Long-Short Term Memory)
  - GRU (Gated Recurrent Unit)
- Walk forward validation is used for cross-validation.
- Hyperparameter tuning is conducted as well for each model.

**DemandForecasting.png**
- Overview of an end-to-end architecture built from scratch for demand forecasting.
- Below describes each system's role:
  - S3 as the data lake
  - Snowflake as the data warehouse/mart
  - AWS Lambda as the data pipeline between the data lake and the data warehouse
  - Tableau as the visualisation tool for the forecasting results

**mock_kaggle.csv**
- Dataset used for DemandForecasting.ipynb
- Dataset available [here](https://www.kaggle.com/code/muhamdsalem/retail-salestime-series-analysis/input).
