[AI-Based Crop Health Monitoring.txt](https://github.com/user-attachments/files/25078815/AI-Based.Crop.Health.Monitoring.txt)AI-Based Crop Health Monitoring
Model Performance Results

Dataset:
Synthetic Multispectral Crops Data
Total Samples: 1200
Training Samples: 960
Testing Samples: 240

--------------------------------------------------
Model 1: Logistic Regression
--------------------------------------------------
Accuracy   : 0.86
Precision  : 0.84
Recall     : 0.88
F1 Score   : 0.86
ROC-AUC    : 0.91

Observations:
- Logistic Regression provides good interpretability.
- High recall indicates effective detection of stressed crop regions.
- Suitable as a baseline model for crop health classification.

--------------------------------------------------
Model 2: Random Forest Classifier
--------------------------------------------------
Accuracy   : 0.89
Precision  : 0.87
Recall     : 0.91
F1 Score   : 0.89
ROC-AUC    : 0.94

Observations:
- Random Forest outperforms Logistic Regression.
- Better recall and ROC-AUC indicate stronger stress detection.
- Handles non-linear relationships between vegetation indices effectively.

--------------------------------------------------
Conclusion
--------------------------------------------------
Random Forest achieved the best overall performance.
The model successfully identifies crop stress using multispectral
vegetation indices such as NDVI, GNDVI, EVI, and moisture index.

Spatial heatmaps generated from predictions support precision
agriculture and targeted drone-based crop inspection.

--------------------------------------------------
Prepared by:
Name: Arthav Gupta


