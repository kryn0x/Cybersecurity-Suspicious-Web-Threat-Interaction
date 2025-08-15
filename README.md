# Cybersecurity-Suspicious-Web-Threat-Interaction
This project analyzes web traffic logs to detect suspicious or potentially harmful activities using Machine Learning. It follows a step-by-step data analysis and anomaly detection workflow based on AWS CloudWatch web traffic data.
📌 Project Overview

Domain: Data Analysis / Cybersecurity

Goal: Detect anomalies in web interactions and identify suspicious activities

Dataset: AWS CloudWatch suspicious traffic logs

Tools & Libraries:

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

📂 Dataset Information

Each record contains:

bytes_in – Bytes received by the server

bytes_out – Bytes sent from the server

creation_time & end_time – Session timestamps

src_ip & src_ip_country_code – Source IP details

protocol – Connection protocol used

dst_port – Destination server port

detection_types – Type of detection applied

📊 Steps Performed

Data Import & Basic Overview – Loaded dataset and explored structure

Data Preprocessing – Removed duplicates, handled missing values, standardized formats

Exploratory Data Analysis (EDA) – Visualized traffic patterns, protocol usage, and suspicious ports

Feature Engineering – Created session_duration and avg_packet_size

Visualization – Country-based analysis, suspicious port activities, traffic trends

Anomaly Detection – Used Isolation Forest to detect suspicious sessions

Anomaly Visualization – Scatter plot showing normal vs suspicious traffic

Report Findings – Key insights and cybersecurity implications
