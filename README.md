# Camouflaged_Animals

This is the repository for my camoulaged animal detection models using YOLOv8. Tseting sets are too large for upload, but val and test sets can be found for each model. 

## CAMO_Identification
This contains the model and dependencies for the YOLOv8 identification process. The train dataset is too large to upload, but can be downloaded from google drive at https://drive.google.com/drive/folders/1h-OqZdwkuPhBvGcVAwmh0f1NGqlH_4B6
In order to test the model against images, refer to the CAMO_test_suite.pynb

Metrics and results from the training process can be found in the CAMO_train_results folder. The model itself can be loaded from the "best.pt" file inside the "weights" folder there.

## MoCA_Classification
This contains the model and dependencies for the YOLOv8 classification process. The train and validation datasets are too large to upload, but can be found at: https://www.robots.ox.ac.uk/~vgg/data/MoCA/
This model is still under development, and requires further encoding to be fully functional.
