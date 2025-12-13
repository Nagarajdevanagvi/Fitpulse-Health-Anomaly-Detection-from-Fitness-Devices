# FitPulse – Health Anomaly Detection from Fitness Devices

## Milestone 1: Data Collection and Preprocessing

### Objective
To collect and preprocess fitness tracker data including heart rate, steps, and sleep parameters.

### Dataset
Wearable fitness tracker dataset in CSV format.

### Preprocessing Steps
- Imported raw fitness data
- Normalized timestamps to UTC
- Interpolated missing values
- Derived sleep indicator from heart rate and step count
- Resampled data to a one-minute interval

### Output
- clean_fitness_data_minute.csv

### Technologies Used
- Python
- Pandas
- NumPy

