# Capstone_Final_Report

# Index:

- Provisional Machine Learning Models in [Notebook](https://github.com/ianhernandezz/Capstone_Final_Report/tree/main/Notebooks) folder. 
    - Provisional_ML_RF_1 - with all features
    - Provisional_ML_RF_2 - no I.D or inspection score
    - Provisional_ML_RF_3 - no violation description
    - Provisional_ML_RF_4 - no violation description, score, or I.D
- Data cleaning and exploration files in [ML_PreProcessing](https://github.com/ianhernandezz/Capstone_Final_Report/tree/main/ML_Preprocessing)folder
- Presentation in [PowerPoint](https://docs.google.com/presentation/d/1ffB2AwLspXSwZHfQvp-hxV4Sp1jOLb_QtWpa1Kn_XQU/edit?usp=sharing). 
- SF_Restaurant_Scores_Standard.csv  in [Data](https://github.com/ianhernandezz/Capstone_Final_Report/tree/main/Data) folder. 
- [Tableau Dashboard](https://ianhernandezz.github.io/Capstone_Final_Report/)
- [Final ML Model](https://github.com/ianhernandezz/Capstone_Final_Report/blob/main/Capstone_ML_Final.ipynb)
- Communication Protocols 


# Project Timeline 

**Week 1 (March 7-13th)**

Ian Hernandez 

- Created the main repository for the project to be updated weekly (or as needed). Branches were created for both Jayce and Kevin. Folders were also created to organize the workflow of the project. 


Jayce Cox

- Read the csv file into Jupyter. Created a provisional Machine Learning model.


Kevin Estrada

- Found the data set and hosted the data into PGadmin.


**Week 2 (March 14th-20th)**

Ian Hernandez 

- This week my role has switched from last week, to be taking on the role to set up the database for merging and joining data sets and get it prepared for Machine Learning. 
- Update March 20th - an attempt was made on database but ran into an issue with importing - it was picked up by Kevin Estrada(was able to create database with joins and merges). 
- I picked up the tasks of pre-processing the new csv file to get it ready for machine learning. And additional task of google slides was picked up. 
- Stage 2 pre-processing complete. CSV file is ready for ML (additional 3 columns were dropped). 

Jayce Cox 

- Prepared the [ML_PreProcessing](https://github.com/ianhernandezz/Capstone_Final_Report/tree/main/ML_Preprocessing) data for the Machine Learning:
    - Drop "inspection_id" and "inspection_score"
    - Encode the input features
    - Converted inspection_date to "Month" and encode "Month" as a number. 
    - Drop inspection_date 
    - Encode the data using get_dummies
    - Split the data between test and train. 
    - Apply StandardScaler
    - Fit the train data
    - Scale the input data
    - Create a Random Forest Classifier
    - Fit the model and make predictions using the testing data. 
    - Evaulate the model using accuracy score, Confusion Matrix, and Classification Report. 
- Created slides with results of the Machine Learning.
- Created a slide detailing our next steps. 

Kevin Estrada
- Cleaned Original Data Set and Merged with Additional Data Set:
    - Dropped uneccesary colums
    - Dropped all rows that has a Null value 
    - Changed columns to Int data type
    - Grabbed all postal codes that had the same postal code in both lists
    - Looped over data to remove extra postal codes of both original and additional data sets
    - Created the table in postgress for both original and addtional data set
    - Merged the both data sets on postal codes
    - Uploaded data for ML learing 


**Week 3 (March 20th-27th)**

Ian Hernandez 
- Created a new CSV for the purpose of Tableau
- Created a dashboard on Tableau (screenshot provided on powerpoint)
- Assisting on database creation for hosting
- Updated PowerPoint slides for presentation 
- Downloaded and uploaded PowerPoint to repository

Jayce Cox
- Updated [PowerPoint](https://docs.google.com/presentation/d/1ffB2AwLspXSwZHfQvp-hxV4Sp1jOLb_QtWpa1Kn_XQU/edit?usp=sharing) and notebook with description of preliminary data preprocessing
- Updated peresentation slides and notebook with description of feature engineering and selection
- Updated peresentation slides and notebook with description of how data was split
- Updated peresentation slides and notebook with explanation of model choice. 

Kevin Estrada
- Uploaded data on Google Big Query to be able to connect to juypter notebook
- Updated [PowerPoint](https://docs.google.com/presentation/d/1ffB2AwLspXSwZHfQvp-hxV4Sp1jOLb_QtWpa1Kn_XQU/edit?usp=sharing) to explain what will be included in "Data preprocessing" and "Data details", "Data storage"


**Week 4 (March 27th-April 3rd)**

Ian Hernandez
- Created further additions and rivisions to the [PowerPoint](https://docs.google.com/presentation/d/1ffB2AwLspXSwZHfQvp-hxV4Sp1jOLb_QtWpa1Kn_XQU/edit?usp=sharing).
- Helped organize the repository 
- Helped develope the story for the project

Kevin Estrada
- Assisted with the machine learning notebook. Bining values, additional resampling techiques. 
- Worked on the database to help retreive additional csv.
- Assisted with updating google slides notebook. 

Jayce Cox

- assisted with resampling the model
- updated google slides with new ML model results

**Week 4 (Aril 3rd-April 7th)**

Ian Hernandez

- Created links to sections within readme file
- Polished powerpoint sections
- Created a Tableau Dashboard wiht assistance of the team
- Created a webhosting for the dashboard to be accessed by anyone

Kevin Estrada

Jayce Cox


# Communication Protocols

- First step daily - do a pull to the individual clones of the main branch 

![Commits](./Images/Screen%20Shot%202022-04-06%20at%207.11.27%20PM.png)

![Branches](./Images/Screen%20Shot%202022-04-06%20at%207.11.05%20PM.png)

- Use of Slack for meetings and updates
- Do a git pull of the individual branches to have the most up to date information to prevent discrepencies upon updating
- Make sure to update the main branch and maintain constant communication to make sure everyone knows to perform updates to the clones. 
- Make sure not to work on the same file at the same time as that will create discrepencies for update. 
