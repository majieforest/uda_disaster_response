# Disaster Response Pipeline Project

### Project Components:

#### 1. process_data.py: Data cleaning pipeline
        This script does the following :
            Loads the messages and categories datasets
            Merges the two datasets
            Cleans the data
            Stores it in a SQLite database

#### 2.train_classifier.py: Machine learning pipeline
        This script does the following :
            Loads data from the SQLite database
            Splits the dataset into training and test sets
            Builds a text processing and machine learning pipeline
            Trains and tunes a model using GridSearchCV
            Outputs results on the test set
            Exports the final model as a pickle file
        
#### 3. run.py: Flask app 
        This script is contains the app and the user interface used to predict results and display them.
    
    
#### 4. templates: folder containing the html templates
