# Patient Records Management System (PRMS)

The Patient Records Management System (PRMS) is a Python-based desktop healthcare application designed to securely manage, store, and analyze patient records. Built with a Tkinter graphical user interface and powered by an SQLite database backend, the system provides a structured and efficient environment for handling clinical data in an offline setting.

PRMS enables healthcare data management through an intuitive interface that supports patient record creation, modification, deletion, and search functionality. The application is designed to streamline documentation processes while maintaining reliable data persistence and structured storage.

## Overview

The system combines database management, rule-based AI logic, and visual analytics into a unified desktop solution. It assists users in identifying high-priority cases, tracking historical trends, and generating meaningful insights from stored patient data.

The integrated reporting module visualizes healthcare trends and distributions, supporting data-driven observation and analysis.

## Core Functionalities

1. **Clinical Data Management** – Full CRUD (Create, Read, Update, Delete) operations for patient records including demographics, diagnosis, clinical notes, and chronic/acute classification.

2. **Risk Assessment System** – Rule-based classification of patients into risk levels (High, Medium, Low) based on defined health indicators.

3. **Admission Recommendation Logic** – Intelligent suggestion mechanism for patient admission decisions.

4. **Automated Follow-Up Suggestions** – Generates follow-up timelines based on patient condition.

5. **Similarity Detection** – Identifies historically similar patient cases within the database.

6. **Data Visualization & Reports** – Graphical representation of:
   - Gender distribution  
   - Chronic vs Acute cases  
   - Top diseases statistics  
   - Monthly patient trends  
   - Age distribution analysis  

## Technologies Used

- Python  
- Tkinter (GUI Development)  
- SQLite3 (Database Management)  
- Matplotlib (Data Visualization)  
- NumPy (Numerical Processing)  

## Installation & Execution

Install required dependencies:

pip install matplotlib numpy

Run the application:

python prms_main.py

## Project Structure

PRMS/
│── README.md  
│── prms_main.py  
│── ai_helpers.py  
│── prms_reports.py  
│── prms_patients.db  

## Future Enhancements

- User authentication and role-based access  
- Cloud database integration  
- PDF export for reports  
- Advanced machine learning-based disease prediction  

---

This project demonstrates practical implementation of GUI development, database integration, healthcare data management, and intelligent rule-based analytics within a structured Python application.

