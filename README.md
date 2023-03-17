# CrowdfundingETL
* The goal of project 2 was aimed tohelp us apply what we hae learned how to perform extract data, transform, and load into a single warehose. ETL will help to gather data from diffrent sources, clean, transform, and load (store) in a single source (database) for easy access and analize the data. The task divided into foour main categories:creating Category and Subcategory DataFrames, Campaign DataFrame, Contacts DataFrame,Crowdfunding Database. We, the two team members divided the task eqully and performed the tasks and screenshots of examples of our work is hsown below. We cearted a GitHub respository and shared it to work independetly or as a group.
* 
1. creating Category and Subcategory DataFrames:

* First we have imported the excel data files and read into Pndas dataFrame.
![image](https://user-images.githubusercontent.com/117956888/225741748-4cbbd612-0dac-4f21-8058-287a9e32b7f0.png)
Then we checked a breif summary of the information  what is in the DataFrame 
![image](https://user-images.githubusercontent.com/117956888/225742098-18e4839a-d726-41cd-bce7-5221861bdd8d.png)

* Then after some cleaning and data transforamation we craeted Category and Subcategory DataFrames
* ![image](https://user-images.githubusercontent.com/117956888/225742710-1815e4da-5c56-4860-8bf3-45c23c43d24f.png)

![image](https://user-images.githubusercontent.com/117956888/225742924-8ae3305a-bcea-4cef-b933-9e885aeaee5d.png)

Finally wie exported Category and Subcategory data into CSV files
![image](https://user-images.githubusercontent.com/117956888/225743781-cc9cd661-4fa7-4012-b1d7-e3e0b9a89bf3.png)

2. Creating Campaign DataFrame:

For this 1st we crated copy of the croudfunding_info_df and a nd named campaogn_df and continued the datavextraction and transformation activity
![image](https://user-images.githubusercontent.com/117956888/225744472-6ddd3843-0d4d-4697-9c6e-11dde991ecf6.png)
Example of data transformation and reading data types
![image](https://user-images.githubusercontent.com/117956888/225744727-5448fcbd-127d-4f9d-945d-67f8d408d384.png)

Merging Category and Subcategory DataFrames
![image](https://user-images.githubusercontent.com/117956888/225745137-947a6127-98b3-4922-baf1-bfe614e8ddf2.png)

Then we cleaned the data and exported to CSV.
![image](https://user-images.githubusercontent.com/117956888/225745415-acd31d76-8907-4cdc-b585-9b377b95bf78.png)

3. Creating Contacts DataFrame: for this  1st we read the contacts  excel file that  was in the resources folder.
![image](https://user-images.githubusercontent.com/117956888/225745818-cc9fa9dc-736a-4a9a-b9dc-34d5e0793679.png)

Then we did data extraction and created dictionaries

![image](https://user-images.githubusercontent.com/117956888/225746119-2d236cc9-e11a-456b-b16e-706800cc54bc.png)

we continued data transformation to get the need columns with contact_id,	email,	first_name, and	last_name. then we reordered the columns to put the emial address at the last column.
![image](https://user-images.githubusercontent.com/117956888/225747129-f047f1dc-c096-485d-ab9c-e55fa72dc87d.png)

Finally we check the data types and exported the data into CSV file.

![image](https://user-images.githubusercontent.com/117956888/225747292-3853aad0-56f9-440d-ae2f-c9956d417d32.png)

4. Creating Crowdfunding Database:
For this  we did inspect the four CSV files, and then sketched an ERD of the tables by using QuickDBDLinks to an external site. We useed the information from the ERD to create a table schema for each CSV file. We saved the database schema as a Postgres file into our GitHub repository. After this we created Create a new Postgres database and imported the CSV files using the database schema nto its corresponding SQL table.
Finally we Verified that each table has the correct data by running a SELECT statement for each table.

![image](https://user-images.githubusercontent.com/117956888/225748817-5fcd0f94-d9cb-4e26-99e7-fc4cd3bf99f9.png)


<img width="600" alt="Screenshot 2023-03-16 at 5 50 51 PM" src="https://user-images.githubusercontent.com/112666732/225783815-3fc07fb4-ad7b-4cf5-8020-3e55d34c2465.png">

# Optional excercise
 We also completed the optional Regex method to create the contact DataFrame.

