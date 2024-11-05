##Project Repository Structure
This repository is structured to streamline data processing, modeling, and UI integration. Below is an overview of each folder and its purpose.


**🚀 Main Application**

**main_app.py:** The main entry point for running the project. This script leverages various modules from the src directory to function.




##Folder Structure



**📁 data_dump**
This folder is used for storing any intermediate data generated during processing.


**📁 data_processing**
Contains scripts that handle data-related operations, including downloading, processing, and feature engineering.


---- **data_download.py:** Download all project data using this script. All raw data sources are processed here before further use.

---- **feature_engineering.py:** Handles all data manipulation and feature engineering for the project.
(Add additional scripts here if needed for data processing.)



**📁 final_data**
Stores the final datasets used for model training. All custom datasets generated through the Model UI are stored here.



**📁 model**
Holds all modeling-related scripts, including training and prediction modules.


---- **train_model.py:** Script to train models.

---- **predict_model.py:** Reads the trained model from train_model.py and performs predictions on the specified dataset.
(Add additional model-related scripts if required.)



**📁 model_artifacts**
This folder stores models trained by train_model.py. Only a single pre-trained model (used by Product UI) will be retained here. Models generated through the Model UI by the evaluator will also be stored here.



**📁 raw_data**
Stores downloaded raw data, structured into subfolders:

---- **cricksheet_data:** Contains raw data downloaded exclusively from Cricksheet.

---- **Additional_data:** Stores raw data from other sources, if applicable.



**📁 UI**
This folder contains all files related to the user interface.



**📁 rest**
Use this folder for any requirements not covered by the above categories.


**📁 out_of_sample_data**
It currently has sample dummy data. It is in the exact format which we will be evaluating for the matches in the duration of 4th Dec till 14th Dec.


**📁 docs**
Put your documentation and working demo of the complete project here. 
Working Video demo should encorporate, everything including setting up github repo on local and then hosting the UI and working of both Project and Model UI.

