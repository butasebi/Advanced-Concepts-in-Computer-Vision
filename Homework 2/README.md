1. the libraries required to run the project including the full version of each library:

os
numpy == 1.20.3
opencv_python == 4.6.0.66
tensorflow == 2.11.0
pickle5 == latest
matplotlib == 3.4.3

2. How to run the tasks:


ATTENTION!!! ALL THE PATHS MENTIONED BELOW MUST ALREADY EXIST TO WORK!

Task1 + Task2: run all the cells
Task1: run all the cells until the Markdown "Task2"
Task2: run all the cells

the path variables at the begging of the code represent:

from_saved_model = True/False if you want to load the model for task1 from a local folder (by default True)

from_saved_model_task2 = True/False if you want to load the models for task2 from a local folder (by default True)

saved_model_path = the path to the task1 model

saved_model_task2_andy_path = the path to the task2 model for andy
saved_model_task2_louie_path = the path to the task2 model for louie
saved_model_task2_ora_path = the path to the task2 model for ora
saved_model_task2_tommy_path = the path to the task2 model for tommy

task1_predictions_save_path = the path to the folder where we will save the predictions for task1

task2_predictions_save_path = the path to the folder where we will save the predictions for task2

task1_ground_truth_path = path to task1 ground truth file
dataset_test_path = path to task1 dataset (the folder that contains the images)

The following files will be created from the tasks:

Task1:

detections_all_faces.npy
file_names_all_faces.npy
scores_all_faces.npy

Task2:

detections_andy.npy
file_names_andy.npy
scores_andy.npy

detections_louie.npy
file_names_louie.npy
scores_louie.npy

detections_ora.npy
file_names_ora.npy
scores_ora.npy

detections_tommy.npy
file_names_tommy.npy
scores_tommy.npy
