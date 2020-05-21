# Disaster Response Pipeline Project

## Table of Content

 1. [Objective and a short summary](#objective)
 2. [Whole Setup process](#setup) 
 3. [License](#Licence)
 4. [Running the file](#run)
 5. [Moving forward](#forward) 
     * what we can together 


<a name="objective"></a>
## Objective 

This project aim to build a NLP model to categorize the message in a real time .
The dataset contained already labelled tewwts and messages from real disasters.
and also the project is a part of udacity datascience course .

This project is mainly compost of three parts :
 
 1. Processing part
    * load the data and categories the dataset
    * it also merge two dataset
    * and then stores in a SQLite database

2. Machile learning Pipeline 
    * load the data from the sqlite data 
    * splits it for training and testing and do respective jobs 
    * At last export the final model as a pickle model 

3. Running a web apps which can predict the output.  