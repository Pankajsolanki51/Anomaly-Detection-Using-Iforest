# Anomaly-Detection-Using-Iforest
##### 1.Overview
Project Details
 In this project, we use NAB-dataset, which is a novel benchmark for evaluating algorithms for anomaly detection in several fields.There are 58 timeseries data from various kind of sources.
Real data
realAWSCloudwatch
realAdExchange
realKnownCause
realTraffic
realTweets
Artificial data
artificialNoAnomaly
artificialWithAnomaly In these dataset above, I picked up and analyzed 'machine_temperature_system_failure' from realKnownCause dataset based on my buissiness interests.
Goal of this project
Practice data pre-processing technique
Practice EDA technique to deal with time-series data
Practice visualising technique
Practice anomaly detection modeling technique(Isolation Forest)
Practice improving model interpretability technique(SHAP)

 ##### Load the dataset
As above, we use 'machine_temperature_system_failure.csv' for our analysis.
According to dataset information, it has the following features :
Temperature sensor data of an internal component of a large, industrial mahcine.
The first anomaly is a planned shutdown of the machine.
The second anomaly is difficult to detect and directly led to the third anomaly, a catastrophic failure of the machine.
