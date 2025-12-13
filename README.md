# CISC600 Deep Learning Course Project
Dhrishti Hazari and Sarah Binder
CISC6000 Deep Learning
Project
Due Dec 8 2025

Detecting High Arousal and Low Emotional Valence Images to Inform Viewer Discretion

## Datasets
Please note that the datasets containing images are stored in Google Drive due to size restrictions on GitHub. Details on requesting access are below.
1. EmoSet accessed via HuggingFace: https://huggingface.co/datasets/Woleek/EmoSet-118K
2. NAPS(Nencki Affective Picture System)
	Data in the NAPS_Data Folder
3. OASIS(Open Affective Standardized Image Set)
	Data in the OASIS_Data Folder
4. Radesky YouTube Dataset - Images Already Classified in the Radeskey Paper
	Data in the Redesky_YT_Dataset Folder
5. YT_images_exploratory
	Images that we personally pulled to label

 ## Code
FINAL RUN: Our final code! Ensure that you change your path in the first line
YT_Dataset: Used to pull in youtube data and rate them individually as well as created a combined valence/arousal rating using averages of every person's results

##Other
All .pth files: Weights of models already run, can be loaded in to the model to prevent re-runs
Final_annotations.csv: Average valence/arousal rating of youtube dataset
Presentation

## Steps to Run

1. Run the FINAL RUN.ipynb file!
2. ENSURE TO ENTER IN THE PATH WHERE YOU HAVE STORED ALL FILES
3. Note that model weights are stroed within a folder on google drive.
4. Note that when loading in NAPS data you will need to edit the path_name. NAPS_H is linked directly below. In our code NAPS_H is nested within NAPS_Data.
5. If you would like to test one of your own images, add an image to “Redesky_YT_Dataset” and save it as “im_{xxx}” Results will be listed right under the Block labeled “Check Below For Your Results” - simply find your image! “True” means it was censored, “False” means it was not.

## Google Drive Paths to Image Datasets and Model Weights (Request Access)
1. NAPS_H https://drive.google.com/drive/folders/1WnDMiHtGP8WBshoYuSvQxfKkrjJ06J28?usp=sharing
2. OASIS_data https://drive.google.com/drive/folders/1djtJIebk_NRWAWVrmOOlIHGHU-GSLgLx?usp=sharing
3. Radesky_YT_Dataset https://drive.google.com/drive/folders/1239OKr1z3vboAESEqtvuKsGB2QOaT4F9?usp=sharing
4. YT_images_exploratory https://drive.google.com/drive/folders/1rVXeFZ6tZYdN7ZbR31ZvwrvyXys9Mo3T?usp=sharing
5. All Model Weights https://drive.google.com/drive/folders/1ARb06NwypgfhgnUKQ5AJIvCIxFRCQgQe?usp=sharing
