# Plety_peak_Detection
Detection of Artifacts and classification and detection of peaks in plethysmographic signal  

# data
This folder contains all of the patient data, in each respective notebook there is a section that allows one to import the data.

# peaks
This folder contains all of the labelled peaks from the data, more precisely it contains the times at which the peak occurs in the data. 
In the Peak Detection notebook there is a section that allows one to create a label of 0 or 1 for each time, 0 if a peak is absent at that point,
1 if the peak is present.

# Artefact_Detection.ipynb
This notebook allows one to train a model to detect the artifacts in the data.

1) Import the data
2) Create a dataframe with all of the data inserted
3) Train the model
4) Test the model on data with no artifacts in it
5) Look at the prediction of the location of the artifacts

# Peak_Detection.ipynb
This notebook allows one to train a CNN model to detect the peaks in the data.

1) Import the data
2) Create a dataframe with all of the data inserted
3) Train the CNN
4) Test the CNN model on a test patient
5) Look at the prediction vs actual peaks
