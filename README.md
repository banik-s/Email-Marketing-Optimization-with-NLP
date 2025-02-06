
## Email Marketing Campaigns Optimization Model with NLP

Our project draws on data from thousands of email marketing campaigns to create a tool which predicts the outcome of a marketing message in terms of open rate, CTR (Click Through Rate) and CTOR (Click Through Open Rate) scores.

The model wants to prevent marketers from sending campaigns with predicted scores lower than their industry benchmarks without having revised the content of their messages first.

The project also provides a multiclass classifier which aims to predict the vertical or sector of a company based on the text content of its campaigns.




#### `01_Main_Model`

It contains the methodology of the project with printed outputs. It starts with an exploratory analysis of the input data, looks into different feature engineering steps (including texts feature engineering using NLP), and finishes with the implementation of three machine learning models to detect Open Rate, CTR and CTOR results.

Notebooks `07_First_model_Model_Selection`  & `08_First_Model_predicting_sectors` within `Main_Model` contain a secondary model also called `Vertical_Model` which detects the sector or vertical of a given company based on the text content of its campaigns.

The folder named `languages` in `01_Main_Model` shows some other examples of running this `Vertical_Model` with data in various languages: Spanish, English, French and Portuguese.


#### `02_Scripts`

It contains nine PY files with the scripts of the most important steps developed in `01_Main_Model`.

#### `campaigns`

This module contains the classes used for the data analysis and transformations needed in `01_Main_Model`.


