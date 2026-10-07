# Industrial Anomaly Detection

An unsupervised machine learning approach for identifying potential abnormal operating periods in cyclone preheater process data.

## Objective

Identify time periods where abnormal operating behavior can be observed from six process variables.

## Dataset

- 377,719 records
- 6 process variables
- 5-minute sampling interval
- 2017–2020

## Methodology

1. Data preprocessing
2. Missing-value handling
3. Exploratory data analysis
4. Isolation Forest anomaly detection
5. Temporal grouping of anomalous observations
6. Identification of potential abnormal periods

## Model

**Isolation Forest**

- `n_estimators = 100`
- `contamination = 0.01`
- `random_state = 42`

## Results

The model identified:

**3,778 potential anomalous observations (~1.0%)**

The longest detected abnormal period lasted approximately **15 hours**.

> These are model-detected potential abnormal operating periods, not confirmed equipment failures.

## Technologies

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn • Jupyter
# Industrial-Anomaly-Detection
# Industrial-Anomaly-Detection
