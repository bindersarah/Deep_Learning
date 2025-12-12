# Deep_Learning
Dhrishti Hazari and Sarah Binder
CISC6000 Deep Learning
Project
Due Dec 8 2025

Detecting High Arousal and Low Emotional Valence Images to Inform Viewer Discretion

## Datasets
 NAPS(Nencki Affective Picture System)
		Data in the NAPS_Data Folder
OASIS(Open Affective Standardized Image Set)
	Data in the OASIS_Data Folder
Redesky YouTube Dataset - Images Already Classified in the Redeskey Paper
Data in the Redesky_YT_Dataset Folder
YT_images_exploratory
	Images that we personally pulled to label

 ## Code
FINAL RUN
Our final code! Ensure that you change your path in the first line
YT_Dataset
	Used to pull in youtube data and rate them individually as well as created a combined valence/arousal rating using averages of every person's results

##Other
All .pth files
Weights of models already run, can be loaded in to the model to prevent re-runs
Final_annotations.csv
Average valence/arousal rating of youtube dataset
Presentation
	Our Presentation

## Steps to Run

1. Run the FINAL RUN.ipynb file!
	ENSURE TO ENTER IN THE PATH WHERE YOU HAVE STORED ALL FILES
2. If you would like to test one of your own images
Add an image to “Redesky_YT_Dataset” and save it is “im_{xxx}” 
Results will be listed right under the Block labeled “Check Below For Your Results” - simply find your image! “True” means it was censored, “False” means it was not.
