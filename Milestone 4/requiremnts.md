Requirements – Milestone 4: Dashboard for Insights

 1. Objective
The objective of Milestone 4 is to design and implement an **interactive Streamlit dashboard** for the *FitPulse Health Anomaly Detection from Fitness Devices* project.  
The dashboard enables users to upload fitness data, dynamically run anomaly detection models, visualize health insights, and download anomaly summary reports.

 3. Execution Environment
- Google Colaboratory (`.ipynb`)
- Python 3.x
- Streamlit executed via Colab using `ngrok` or equivalent tunneling

3. Functional Requirements

 3.1 Dashboard Development
- Develop an interactive dashboard using **Streamlit**
- Dashboard must run inside **Google Colab**
- User Interface should be:
  - Simple
  - Intuitive
  - Easy to navigate
- Dashboard must execute without runtime errors

 3.2 Data Upload & Integration
- Allow users to upload fitness data files in:
  - CSV format
  - JSON format
- Uploaded data must be processed dynamically
- Integrate the following pipelines from previous milestones:
  - Data preprocessing
  - Feature extraction
  - Anomaly detection model
- Users must be able to trigger anomaly detection directly from the dashboard

 3.3 Visualization of Insights
The dashboard must display **interactive visualizations** for:

a) Heart Rate
- Heart rate trends over time
- Highlight anomalies using markers or color differentiation

 b) Sleep Patterns
- Sleep duration trends
- Identification of abnormal sleep patterns

 c) Step Count
- Daily step count behavior
- Alerts for abnormal step activity

 3.4 Filtering Options
- Metric-wise filtering:
  - Heart rate
  - Sleep duration
  - Step count
- Date-wise filtering:
  - Single date selection
  - Date range selection

 3.5 Report Generation
- Generate a downloadable **anomaly summary report**
- Report format: CSV
- Report must include:
  - Metric name
  - Anomaly type
  - Timestamp / Date
  - Anomaly flag or score

 4. Non-Functional Requirements
- Code must be:
  - Well-structured
  - Properly commented
  - Easy to understand
- Notebook must include:
  - Explanations
  - Observations
- Dashboard performance should be responsive for moderate data sizes

 5. Tools & Libraries Required
- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Pyngrok (for Colab execution)

 6. Output Requirements
The following outputs are mandatory:

- Running Streamlit dashboard in Google Colab
- Interactive anomaly visualizations
- Downloadable anomaly summary report
- Screenshots:
  - Dashboard UI
  - Report download confirmation




