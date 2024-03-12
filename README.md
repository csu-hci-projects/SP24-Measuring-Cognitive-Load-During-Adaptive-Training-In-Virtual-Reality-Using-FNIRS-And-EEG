# SP24-Measuring-Cognitive-Load-During-Adaptive-Training-In-Virtual-Reality-Using-FNIRS-And-EEG

This is an extension GitHub repo for the ONR-XR multi-year project that my class project is extending. The original virtual environment has been created by NUILab member Lucas Plabst, linked here:

https://github.com/NuiLab/asTask.git

My class project slightly extends this virtual environment to allow the Lab Streaming Layer (LSL) to be integrated. LSL is crucial for both fNIRS and EEG measures to allow triggers to be sent and for measures to start recording as soon as Meta Quest 3 users begin their training. For simplicity, the code I created and added to the original environment originated in the following link:

https://github.com/labstreaminglayer/LSL4Unity.git

My specific files are available throughout this current repo. To be exact, my modifications include integrating code into Lucas's work so that triggers could be sent at all recorded events and a file describing the steps required to receive the LSL successfully triggers in both the fNIRS and Aurora software.

# Files Included

## How to Run the Project With LSL

Includes the following sections:

* Opening Software / Prepare Hardware
* After Setting Up Participant with fNIRS / EEG / Cap / Head-Mounted Display (Quest 3)
* When Complete
* Data Collection
* Data Analysis
* Self Documentation
