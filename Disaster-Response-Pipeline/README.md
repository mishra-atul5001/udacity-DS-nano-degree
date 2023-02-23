# Disaster Response Pipeline Project

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
