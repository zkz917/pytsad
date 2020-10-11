# Python Time Series Anomaly Detection (PyTSAD)
A Python Toolbox for Time Series Anomaly Detection
Build a platform based on unsupervised learning for multivariate time series anomaly detection.
To enhance advanced BI analysis and provide solutions to answer questions like what the trend is and when we will have to increase our system capacity. 
## Blueprint:
### Feature Engineering
The key point for time series anomaly detection will be the feature engineering. How to select the window size and choose rolling statistics will be chanllenging.  PyTSAD will provide multiple solutions for feature engineering of time series data.
PyTSAD will help you to choose the ideal size of rolling window and within this window it will generate following features:
* Treand
* Seasonality
* Z-score
* PAA representation
* Min/Max/Mean
* Variation

### Models
* Distance based model 
* LOF
* KNN
* IForest
* AutoEncoder

### Type of Time series anomaly

* Point anomaly
* Subsequence anomaly 
* Pattern break
* Frequency change
* Data drifting
