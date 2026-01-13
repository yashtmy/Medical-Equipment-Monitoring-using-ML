# Medical-Equipment-Monitoring-using-ML
This project applies data analytics and machine learning to monitor the health of industrial equipment. Inspired by medical health monitoring systems, the project treats equipment sensor data as vital signs and predicts failure risk to enable preventive maintenance.

## Motivation
Unexpected equipment failure leads to production downtime, quality loss, and increased cost.
By predicting failure risk in advance, maintenance can be scheduled proactively to improve
overall productivity and yield.

## Dataset
Synthetic sensor data was generated to simulate real factory conditions, including:
- Temperature (°C)
- Pressure (bar)
- Vibration (mm/s)
- Operating Hours

Each record is labeled with a failure risk indicator.

## Methodology
1. Exploratory Data Analysis (EDA) to understand sensor behavior
2. Feature selection and preprocessing
3. Machine Learning model training using Random Forest Classifier
4. Model evaluation using accuracy, precision, recall, and confusion matrix
5. Risk-based maintenance recommendation system

## Results
The model achieved strong performance in identifying high-risk equipment.
Vibration and operating hours were identified as the most influential factors for failure risk.

## Improvement Proposal
Equipment is categorized into low, medium, and high-risk groups.
- High-risk: Immediate preventive maintenance
- Medium-risk: Scheduled inspection
- Low-risk: Normal operation

This approach reduces unexpected failures and improves production stability.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Future Work
- Integration with real-time factory sensor data
- Deployment as an AI agent for smart factories
- Extension to anomaly detection models
