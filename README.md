# Capstone_Final_Report

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
- Stage 2 pre-processing complete. CSV file is ready for ML (additional 3 columns were dropped. 

Jayce Cox 

- Prepared the pre-processed data for the Machine Learning:
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

## Data Selection 

**Reason why they selected their topic:**

We selected this topic becuase we found it interesting and thought it would be a great machine learning project. This data set has mulitpe features and we found it possible to merge with an additional data set by the postal code.  


**Description of their source of data**

The source was found on the [Link to website](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores-LIVES-Standard/pyih-qa8i?row_index=0). This website hosts multipe data sets on the San Francisco area.


**Questions they hope to answer with the data**

We hope to determine if a restaurant will have a High, low, or moderate health risk based off numerous features found in the data set.


# Communication Protocols

- First step daily - do a pull to the individual clones of the main branch 
- Do a git pull of the individual branches to have the most up to date information to prevent discrepencies upon updating
- Make sure to update the main branch and maintain constant communication to make sure everyone knows to perform updates to the clones. 
- Make sure not to work on the same file at the same time as that will create discrepencies for update. 
