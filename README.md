**Healthcare Patient Analysis System**


**Overview**


Healthcare analytics is essential for improving patient outcomes and hospital efficiency
This project demonstrates how synthetic patient data can be generated and analyzed using Python
It helps identify trends, patterns, and health risks


**Objective**


•Managing patient data manually is time-consuming and inefficient
•This system helps to:
•Track patient records efficiently
•Identify disease patterns
•Monitor health parameters
•Support better decision-making


**Approach**


The project uses Python tools:
Data Generation – Using Faker to create realistic data
Data Processing – Using Pandas for cleaning data
Analysis – Applying statistical methods
Visualization – Using charts and graphs


**System Design**


The system has four layers:
Data Generation Layer – Creates synthetic data
Processing Layer – Cleans and structures data
Analysis Layer – Performs analysis
Visualization Layer – Displays insights


**Dataset Details**


Patient_ID – Unique identifier
Name – Generated patient name
Age – Between 20 and 80
Gender – Male or Female
Disease – Type of illness
Sugar_Level – Blood sugar level
Heart_Rate – Beats per minute
City – Location
Admission_Date – Admission date


**Data Analysis Performed**


Age and sugar distribution analysis
Disease frequency analysis
Gender comparison
Admission trend analysis
Outlier detection


**Visual Insights**


Histogram – Age and sugar distribution
Bar Chart – Disease frequency
Pie Chart – Gender ratio
Scatter Plot – Age vs Heart Rate
Box Plot – Disease vs Age
Line Graph – Monthly admissions
Stacked Bar Chart – Gender vs Disease


**Key Findings**


Diabetes is common
Older patients have higher sugar levels
Heart rate varies with age
Some months have more admissions


**Project Structure**


healthcare-analysis/
│
├── data/
│   └── patient_data.csv
│
├── notebook/
│   └── analysis.ipynb
│
├── src/
│   └── main.py
│
├── README.md
└── requirements.txt


**Data Privacy**


Synthetic data only
No real patient data used
Maintains privacy and ethics


**Advantages**


Easy to implement
No real data required
Scalable
Good for academic use


**Limitations**


Not fully real-world accurate
No real-time data
Limited medical accuracy


**Future Scope**


Real hospital data integration
AI-based prediction models
Streamlit dashboard
Real-time monitoring


**Learning Outcomes**


Faker for data generation
Pandas for data handling
Data visualization skills
Healthcare analytics basics


**output screenshots**


<img width="751" height="523" alt="image" src="https://github.com/user-attachments/assets/460c5a86-c74e-4a17-b650-91265e746d71" />
<img width="632" height="496" alt="image" src="https://github.com/user-attachments/assets/e8ff7ca6-57f9-4dd6-88ef-ef49ad5cf99c" />
<img width="760" height="429" alt="image" src="https://github.com/user-attachments/assets/8ad271a4-ea1a-4687-840c-e0b7d58fa7a5" />
<img width="760" height="429" alt="image" src="https://github.com/user-attachments/assets/de0bf778-0bce-4b23-a194-f6071c3873dc" />

**Summary**


This project provides a simple and effective healthcare analysis system
Combines data generation, analysis, and visualization
