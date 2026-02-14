# AI-Based Appliance Usage Detection

## Project Overview
This project demonstrates how Artificial Intelligence can detect individual appliance usage using only a single smart meter. Instead of installing separate sensors for each device, the system analyzes total power consumption and predicts which appliances are ON or OFF.
The prototype simulates household appliances and applies machine learning techniques to perform appliance detection, fault monitoring, anomaly detection, and energy awareness visualization.
In simple words,this project detects individual appliance usage from a single smart meter using Machine Learning.

## Problem Statement
In most households, smart meters provide only total electricity consumption. Users cannot identify which appliance consumes how much power. This leads to:
Lack of energy awareness
Power wastage
Difficulty detecting overload conditions
No appliance-level monitoring
## Solution
This prototype which aims to solve this using AI-based non-intrusive load monitoring.It demonstrates the feasibility of detecting individual appliance usage using AI techniques and a single aggregate smart meter signal. It highlights how machine learning can enhance energy monitoring, improve safety, and promote energy efficiency in smart homes.
## Features of the System
### -Appliance-level detection from single smart meter
### -Multi-model training architecture
### -Confusion matrix visualization
### -Feature importance analysis
### -Fault / overload detection
### -Anomaly detection
### -Energy distribution dashboard (Pie chart & Bar graph)
## System Workflow
### ~Simulated appliance ON/OFF behavior (Fan, Fridge, AC, Heater)
### ~Generated aggregate smart meter signal
### ~Extracted statistical features (Mean, Standard Deviation, Maximum)
### ~Trained machine learning models for appliance detection
  #### Machine Learning Approach
 ##### Algorithm Used: Random Forest Classifier
  Separate model trained for each appliance.
  Features Used:
  ###### -Rolling Mean
  ######  -Rolling Standard Deviation
  ######  -Rolling Maximum
### ~The model predicts appliance ON/OFF status using only total power data.
### ~Evaluated model performance using accuracy and confusion matrix
### ~Implemented overload/fault detection
### ~Added anomaly detection using Isolation Forest
### ~Built energy awareness dashboard using visualizations
## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Future Scope
Integration with real smart meter datasets and IoT devices.
