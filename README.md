# Disaster Response Pipeline Project

### Table of Contents

1. [Project Motivation](#project)

2. [Installation and File Descriptions](#file)

3. [Licensing, Authors, and Acknowledgements](#licensing)

   

## Project Motivation <a name="project"></a>

This project serves as the second deliverable in the Data Science Nanodegree @ Udacity. The main goal of this project is to classify disaster or emergency related messages received through different channels. To this end a classification algorithm is trained on thousands of labelled examples of this kind of messages.
    
    
## Installation and File Descriptions <a name="file"></a>

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

Please remember that the above web address will only work if you are running this code on your local machine. Otherwise you would need to replace 0.0.0.0 by tyour server or remote IP address.

Below there is an example of how the app looks like. To classify a new message, you just need to write it on the text box and click on the button.

![screenshot](https://github.com/alvaroof/disaster-response-pipeline/blob/master/Captura.PNG)



## Licensing, Authors, Acknowledgements <a name="licensing"></a>

The author is only me, although since this is a project related to an online degree a great part of the code has been taken from their templates. Professionally I work as a Data Scientist in the healthcare industry, but have little presence on the internet. You can reach me at *ortiz.fernandez.alvaro@gmail.com* should you have any comment or question.



