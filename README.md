# Measuring Cognitive Load During Adaptive Training In Virtual Reality Using fNIRS And EEG

This is an extension GitHub repo for the ONR-XR multi-year project that my class project is extending. The original virtual environment has been created by NUILab member Lucas Plabst, linked here:

https://github.com/NuiLab/asTask.git

My class project slightly extends this virtual environment to allow the Lab Streaming Layer (LSL) to be integrated. LSL is crucial for both fNIRS and EEG measures to allow triggers to be sent and for measures to include time stamps as soon as Meta Quest 3 users begin their training. For simplicity, the code I created and added to the original environment originated in the following link:

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

## Unity _ LSL _ Aurora

Includes all the links, my understanding of each resource, and how they benefit me.

## Modified Code

SimpleOutletTriggerEvent.cs is available for viewing. It is based on the GitHub link in the first section above. The only thing modified is an additional method that does the same as the exit collision method but allows for a non-collision event. Due to unfamiliarity with the provided code, it was easiest not to modify too much.

My modified code is also available in this forked repo:

https://github.com/Jalynnn/asTask.git

# Next Steps

* Modify the code to send a string message and make the ID sent meaningful. This is necessary since the fNIRS Aurora software only picks up on the ID, not the string. This is not a problem with Brain Vision, as the string is recognized.
* Triggers must be sent with every recorded event, not just when the start button is pressed. While keeping the trigger on the start button is good, it also needs to be included in the same code that sends the recorded events. Lucas mentioned a good place to locate this additional code. This still needs to occur.
