# Wearable-Device-Health-Trends-Anomaly-Insights
<img width="550" height="200" alt="image" src="https://github.com/user-attachments/assets/bd6cd4dc-517a-452f-b349-46b1249033ba" />


Project Summary:

This project analyzes wearable device sensor data using Python and Power BI to detect health anomalies and understand physiological trends. The workflow included cleaning and preprocessing the time-series data, feature engineering with rolling averages and temporal extracts, anomaly detection using Isolation Forest, and classification using Random Forest. Power BI dashboards visualize key health metrics and anomalies for intuitive monitoring. The project aims to support early detection of health risks and enable proactive healthcare management.

Dataset:

The dataset was collected from a wearable hardware device developed by me as a college mini project. It includes time-stamped physiological measurements such as heart rate, blood pressure, temperature, and device battery status across multiple patients.

Challenges:

- Handling noisy and incomplete sensor data with missing values required robust imputation techniques.

- Differentiating between normal variations and true anomalies took iterative model tuning and domain knowledge.

- Integrating temporal dependencies and static patient features into prediction models demanded careful feature engineering.

- Balancing model accuracy with interpretability for actionable health insights posed analytical challenges.

Business Impact & Insights:

- Early anomaly identification enables timely clinical responses, potentially improving patient outcomes.

- Visual dashboards facilitate real-time health status monitoring for providers.

- Models help personalize patient care by understanding individual health trends and deviations.

- The solution provides a foundation for scalable remote health monitoring and telemedicine applications.

How Challenges Were Addressed:

- Utilized forward and backward filling within patient groups for missing data.

- Applied rolling windows to smooth sensor noise and reveal underlying trends.

- Fine-tuned Isolation Forest contamination parameters to optimize anomaly detection.

- Combined exploratory data analysis with model validation to ensure reliable predictions.

Future Work:

- Incorporate additional sensor types for richer health profiling.

- Deploy real-time alerting systems using integrated anomaly detection.

- Apply deep learning models to enhance prediction accuracy.

- Expand Power BI dashboards with predictive analytics and user customization.




