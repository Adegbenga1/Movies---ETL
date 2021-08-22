## Movies---ETL
##  Project Overview

 Create of an automated pipeline that takes in new data, performs the appropriate transformations,
 and loads the data into existing tables with final transformations and  loading  the data into an existing PostgreSQL database.
     
## Results
## Write an ETL function to read three data files 
The ETL function was used to create  dataframes from Wikipedia JSON, the Kaggle metadata and MovieLens csv files.
    
  ![image](https://user-images.githubusercontent.com/70987568/130368010-d71eecfd-0431-47c5-8323-f527966229cd.png)
  ![image](https://user-images.githubusercontent.com/70987568/130368018-1b381050-d75e-4233-a2a1-7e304c48334c.png)
   ![image](https://user-images.githubusercontent.com/70987568/130368027-4fa3b133-8507-42d9-895f-dcf1c7777cee.png)


## Extract and Transform the Wikipedia data
  Wikipedia data was transformed by cleaning the data,removing the duplicates ,writing a regular expressions,parsing
  dollars,parsing the Box office data and formatted.
  
  ![image](https://user-images.githubusercontent.com/70987568/130368053-1c682fc3-acb4-4532-99b4-c66911ceba68.png)
  ![image](https://user-images.githubusercontent.com/70987568/130368065-c9b0354b-8d95-469c-a074-91337df2b76e.png)
  ![image](https://user-images.githubusercontent.com/70987568/130368076-e3e11a80-02fb-4b39-83d5-e8867c8d3461.png)



## Extract and Transform the Kaggle and rating data
   The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

![image](https://user-images.githubusercontent.com/70987568/130362348-42059375-5fab-4f10-b07c-f2f0c2e20cf4.png)
![image](https://user-images.githubusercontent.com/70987568/130362358-826b848e-93e2-40f2-9528-07dced668540.png)
![image](https://user-images.githubusercontent.com/70987568/130362371-2f2f135d-6f30-4c2e-9a7d-38e0664221f2.png)
![image](https://user-images.githubusercontent.com/70987568/130362481-c8b65c00-0dee-4611-96de-07ccf5077a3e.png)

## Load the data to a PostgreSQL Movie Database

