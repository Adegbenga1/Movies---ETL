## Movies---ETL
##  Project Overview
     Create of an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables with final transformations and 
     loading  the data into an existing PostgreSQL database.
## Results
## Write an ETL function to read three data files 
     The ETL function was used to create  dataframes from Wikipedia JSON, the Kaggle metadata and MovieLens csv files.
    

## Extract and Transform the Wikipedia data
  Wikipedia data was transformed by cleaning the data,removing the duplicates ,writing a regular expressions,parsing dollars,parsing the Box office data and formatted.
  ![image](https://user-images.githubusercontent.com/70987568/130362250-57adba6b-6076-4682-8eb9-4c31d28ff845.png)
  ![image](https://user-images.githubusercontent.com/70987568/130362292-ee95e49d-0bd8-40e3-89f4-da33d5552396.png)
  ![image](https://user-images.githubusercontent.com/70987568/130362310-068108fa-5a59-457f-96f8-e965cb92770b.png)
  ![image](https://user-images.githubusercontent.com/70987568/130362501-10217514-cfd8-4703-b80f-7b686164beb8.png)


## Extract and Transform the Kaggle and rating data
   The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

![image](https://user-images.githubusercontent.com/70987568/130362348-42059375-5fab-4f10-b07c-f2f0c2e20cf4.png)
![image](https://user-images.githubusercontent.com/70987568/130362358-826b848e-93e2-40f2-9528-07dced668540.png)
![image](https://user-images.githubusercontent.com/70987568/130362371-2f2f135d-6f30-4c2e-9a7d-38e0664221f2.png)
![image](https://user-images.githubusercontent.com/70987568/130362481-c8b65c00-0dee-4611-96de-07ccf5077a3e.png)

## Load the data to a PostgreSQL Movie Database

