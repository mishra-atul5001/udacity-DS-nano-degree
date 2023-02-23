# Disaster Response Pipeline Project

### Project Overview
In this course, you've learned and built on your data engineering skills to expand your opportunities and potential as a data scientist. In this project, you'll apply these skills to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.

In the Project Workspace, you'll find a data set containing real messages that were sent during disaster events. You will be creating a machine learning pipeline to categorize these events so that you can send the messages to an appropriate disaster relief agency.

### Structure
<img width="419" alt="image" src="https://user-images.githubusercontent.com/22134737/220968785-c19f25ec-061f-4748-9ba0-ece5a25e110b.png">

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/


![image](https://user-images.githubusercontent.com/22134737/220867792-e1c65ff2-e1b8-443c-aa3f-2bff614baed0.png)

![image](https://user-images.githubusercontent.com/22134737/220868415-78afb485-e0d9-40ca-b9ba-2fe15592264e.png)
