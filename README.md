# Fan-Fault-Detection
# Overview
This project demonstrates how to create a machine learning classifier using the Analytics and Machine Learning Toolkit in LabVIEW. To implement this project, you'll need the following:

## Hardware:

* NI CompactDAQ (cDAQ) with analog input and output modules
* NI Sound and Vibration Simulator
* BNC cables

## Software:

* NI LabVIEW 2018
* NI Analytics and Machine Learning Toolkit
* NI DAQmx drivers
* 
# Getting Started
Follow these steps to get started with fan fault detection:

## Hardware Setup:

* Connect two accelerometer sensors to the cDAQ analog input module channels using BNC cables.
* Connect the fan to the analog output module on the cDAQ.

## Run the project:

1. Ensure you have NI LabVIEW 2018 and the NI Analytics and Machine Learning Toolkit installed on your system.
Install the required NI cDAQ drivers.
Data Collection for Training:

2. Open the LabVIEW project and locate the "Data Collection with cDAQ for Training.vi" file.
Execute this VI to collect data from both balanced and unbalanced fans. The code will automatically vary fan speeds and record data, saving it to a file.
Train the Machine Learning Model:

3. Open the "Training ML Model.vi" file in the LabVIEW project.
Use this VI to train a machine learning model with the collected data. Save the trained model.
Deployment and Testing:

4. Open the "Deployment on cDAQ" VI in the project.
Use this VI to test the trained machine learning model's performance on a cDAQ system in a real-world setting.
