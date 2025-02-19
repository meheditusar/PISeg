# PISeg
pressure injury staging with YOLOv8 and ensemble models

#this is one sample code for training the model

step 1. Download the dataset from roboflow, project id: advances-in-wound-care-pi-dataset, or download it from this repository named train, test valid folder

step 2. Reorganize them into images and labels folder, each folder should have train, val, and test subfolders

step 3. Rename the data.yaml file into config.yaml file and also change the dataset structure as described in step 2. Change the dataset directory into the trianing_code

step 4. Run this code into a suitable environment for training with YOLOv8. 
