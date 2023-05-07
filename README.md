# Team DS6 Project - Team Elden Ring

This particular project was a collaboration between [Alison Cordoba](https://github.com/AlisonCG1), [Ajay Kale](https://github.com/AjayNSS), [Smita Misra](https://github.com/smitamisra) and myself. We worked both individually and as a team, bouncing ideas off each other and consolidating it together. For the predictions, we all worked on different models and configurantions, while discussing and building off each other.

# Big G Express: Predicting Derates
In this project, you will be working with fault code data and vehicle onboard diagnostic data to try and predict an upcoming full derate. These are indicated by an SPN 5246. 

You have been provided with a two files containing the data you will use to make these predictions (J1939Faults.csv and VehicleDiagnosticOnboardData.csv) as well as two files describing some of the contents (DataInfo.docx and Service Fault Codes_1_0_0_167.xlsx) 

Note that in its raw form the data does not have "labels", so you must define what labels you are going to use and create those labels in your dataset. Also, you will likely need to perform some significant feature engineering in order to build an accurate predictor.

Additional cleaning tasks:
* Remove faults occurring in the vicinity of the service locations at (36.0666667, -86.4347222), (35.5883333, -86.4438888), and (36.1950, -83.174722)
* Remove faults where the EquipmentID has more than 5 characters.