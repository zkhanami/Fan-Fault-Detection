# Fan-Fault-Detection
# Overview
This project demonstrates how to create a machine learning classifier using the Analytics and Machine Learning Toolkit in LabVIEW. To implement this project, you'll need the following:

### Hardware:

* NI CompactDAQ (cDAQ) with analog input and output modules
* NI Sound and Vibration Simulator
* BNC cables

### Software:

* NI LabVIEW 2018
* NI Analytics and Machine Learning Toolkit
* NI DAQmx drivers

# Getting Started
Follow these steps to get started with fan fault detection:

### Hardware Setup:

* Connect two accelerometer sensors to the cDAQ analog input module channels using BNC cables.
* Connect the fan to the analog output module on the cDAQ.

### Run the project:

1. Data Collection for Training: Open the LabVIEW project and locate the "Data Collection with cDAQ for Training.vi" file.
Execute this VI to collect data from both balanced and unbalanced fans. The code will automatically vary fan speeds and record data, saving it to a file.
2. Train the Machine Learning Model: Open the "Training ML Model.vi" file in the LabVIEW project.
Use this VI to train a machine learning model with the collected data. Save the trained model.
3. Deployment and Testing: Open the "Deployment on cDAQ" VI in the project.
Use this VI to test the trained machine learning model's performance on a cDAQ system in a real-world setting.
