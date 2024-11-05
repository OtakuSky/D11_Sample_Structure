**main_app.py :** This is the only file that we will run, it is supposed to use scripts from src to function.


**folder - data_dump :** use this to dump any intermediate data.

**folder - data_processing :** Any scripts which will handle data related operations needs to be here.

------ data_download.py : all the data which is being used for the project should be downloaded only using this script.

------ feature_engineering.py : any type of data manipulation/feature engineering should be done within this script. 

------ add any other script if needed related to data


**folder - final_data :** use this as data store for your ultimate data which will be used in model for training. All the custom datasets generated through Model UI would also go here.


**folder - model :** modeling scripts here

------ train_model.py : file used to train model

------ predict_model.py : should read the model trained by train_model.py and predict on required duration

------ add any other script if needed related to model


**folder - model_artifacts :** Use this to store models using train_model.py. It will have only one pretrained model which will be used in Product UI. Rest of the models would be generated through Model UI by the evaluator.


**folder - raw_data :** Output of data_download.py

------ folder cricksheet_data : it is downloaded raw data from cricksheet only 

------ folder Additional_data : it is downloaded raw data from other sources if any


**folder - UI:** Files related to UI would go here


**folder - rest:** Use this if you have any other requirements besides mentioned above








