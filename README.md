## End to End Machine learning Project.

SET up the project with Git hub.
1.	Data Ingestion
2.	Data Transformation
3.	Model Trainer
4.	Model Evaluation
5.	Model Deployment
These all will be in CI/CD Pipelines – GitHub Actions
Deployment – AWS
Agenda:
1.	Set up the GitHub repository.
a)	New environment.
b)	Mini project structure. Or setup.py
c)	Requiremnts.txt
2.	Src source Folder and build the package.

Data Ingestion.py: Read the data base from specific database which is specifically say it as data ingestion so data ingestion is a part of module so that can be our component.
all code related which are required to read a data will be in data ingestion.

Data Transformation.py:
all code related how to transform data probably how to change the categorical features into numerical features, how to handle lable coding.

Model trainer.py:
all code related which shows how many types of models, solving regression problems.

Pipeline.py: There are two pipelines considered those are Train_pipeline and predict_pipeline.
Train pipeline.py: Basically from train pipeline we try to trigger or call these components.
Predict_pipeline.py: Basically when model is basically creaated and want to predict for the new data and write over here. 

Entire project implementation will be be happening inside the source. hence inside source there are 3 important files.
1. logger.py
2. exception.py
3. any fucntionality(utils.py)- which is used in any applications. like read any database or can create my client like mongodb client or want to save my model into the cloud and can write the code over here.
