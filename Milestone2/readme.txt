 Milestone 2: Feature Extraction and Modeling

Objective
This milestone focuses on extracting meaningful time-series features from fitness data, modeling temporal trends, and identifying behavioral patterns to support health anomaly detection.

 Dataset
The cleaned and time-aligned dataset generated in Milestone 1 is used, containing heart rate, steps, and sleep metrics at 1-minute resolution.

 Methodology

 Feature Extraction
Automated time-series feature extraction was performed using TSFresh to capture statistical and frequency-based characteristics. Feature selection was applied to retain informative attributes.

Trend Modeling
Facebook Prophet was employed to model daily and weekly seasonality. Deviations between actual and predicted values were computed to identify unusual patterns.

Behavioral Clustering
Unsupervised clustering techniques were applied on standardized features. Dimensionality reduction enabled visualization of normal and atypical behavior clusters.

Frontend Interface
A Streamlit-based frontend was developed to visualize extracted features, trend forecasts, residuals, and clustering outputs interactively.

Tools Used
Python, Pandas, TSFresh, Facebook Prophet, Scikit-learn, Streamlit, Google Colab

Observations
Clear seasonal trends were observed in heart rate data. Residual analysis highlights potential anomalies, and clustering reveals distinct behavioral groups.

