Project Name:
PHAD-Public Health Anomaly Detection

Objective:
Detect anomalous spikes in influenza-like illness (ILI) trends using real-world epidemiological time-series data.

Datasets Used:
CDC ILINet Data: %ILI visits by week and age group

CDC Lab Surveillance Data: Weekly specimen counts by influenza strain

Source: CDC FluView

Tech Stack:
Language: Python

Libraries: pandas, scikit-learn, PyOD, Plotly, Gradio

Model & Methods:
Isolation Forest (Unsupervised Anomaly Detection)

StandardScaler for feature normalization

Time-series filtering and merging via pandas

Output:
Cleaned, merged dataset with anomaly labels
Interactive dashboard for trend and anomaly visualization# PHAD-Public-Health-Anomaly-Detection



##NOTE-HERE in dataset, I used ILINET DATA and LAB PUBLIC DATA , there weere three csv files. If u want to make a change by adding data, just edit the load_data.py and merged_data.py. AND the data used here is from 2023 to 2025.
