AI-Powered Network Intrusion Detection System (NIDS)
Project Overview

The AI-Powered Network Intrusion Detection System (NIDS) is a Machine Learning–based security application designed to identify malicious network activity in real time. The system analyzes network traffic patterns and classifies them as Benign or Malicious using a Random Forest classifier, providing an interactive dashboard for monitoring and analysis.

This project was developed as part of a Cyber Security Internship, with a focus on applying AI techniques to real-world security challenges.

Problem Statement

Traditional rule-based intrusion detection systems struggle to detect modern and evolving cyberattacks. There is a need for an intelligent system that can automatically learn traffic patterns and accurately identify suspicious behavior in network environments.

Solution

This project implements an AI-driven intrusion detection approach that:

Learns network traffic behavior using Machine Learning

Detects abnormal patterns indicating potential cyberattacks

Provides real-time insights through an interactive dashboard

Key Features

Machine Learning–based attack detection using Random Forest

Simulated network traffic aligned with CIC-IDS-2017 dataset structure

Interactive Streamlit dashboard

Real-time packet analysis and prediction

Performance evaluation with accuracy metrics and confusion matrix

User-controlled model parameters (training split, number of trees)

Technology Stack

Programming Language: Python 3

Machine Learning: Scikit-learn (Random Forest Classifier)

Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Web Framework: Streamlit

Project Structure
AI_NIDS_Project/
│
├── app.py
├── requirements.txt
└── README.md

How the System Works

Synthetic network traffic data is generated to simulate real-world conditions.

The dataset is split into training and testing sets.

A Random Forest model is trained on network traffic features.

The model evaluates performance using accuracy and confusion matrix.

Users can input live traffic parameters to test whether traffic is benign or malicious.

Dataset Information

For demonstration purposes, the system uses simulated network traffic data that follows the structure of the CIC-IDS-2017 dataset.
The architecture supports real-world dataset integration if required.

Installation & Execution

Install dependencies:

pip install -r requirements.txt


Run the application:

streamlit run app.py


Access the dashboard at:

http://localhost:8501

Demo

Demo Type: Local Streamlit Dashboard

Demonstration: Model training, performance metrics, and live traffic analysis

Screenshots are included in the project documentation and presentation.

Internship Context

This project was developed as part of a Cyber Security Internship to demonstrate:

Practical application of AI in security systems

Understanding of intrusion detection concepts

Ability to design and implement an end-to-end ML solution

Conclusion

The AI-Powered Network Intrusion Detection System showcases how Machine Learning can enhance cybersecurity by detecting malicious activity with improved accuracy and adaptability. The project serves as a strong foundation for further research and real-world deployment in network security environments.

Author

Abhi Gandesri
Cyber Security Intern
