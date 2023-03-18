# DATA CLEANING 
![Data cleaning](https://user-images.githubusercontent.com/92938944/226064114-17cadf58-fb67-4422-a04b-fb8a9edeee64.png)

This cleaning exercise was started on twitter which i joined to pratice data cleaning. 
In every organizaton gathering and storing of data is important to growth and development, but before any personel in the Data field generates insights 
cleaning data is practically the first step. 
Cleaning Data provides the foundaton in understanding the data and also reducing skewness of data.

Data cleaning is the process of fixing or removing incorrect,  duplicate, or incomplete data within a dataset. When combining multiple data sources, there are many opportunities for data to be duplicated or mislabeled.For starters, it’s good practice to keep on top of your data, ensuring that it’s accurate and up-to-date. The general importanceof data cleaning is your results will be flawed with imcomplete data

## FIFA 21 Data Cleaning Challenge
I love playing video games especially the EA sport Franchise game called FIFA. This Data was gotten from a shared link: https://www.spaziogames.it/fifa-21-copertina-ufficiale/ to practice my Data cleaning skills.
                          
![FIFA-21-1](https://user-images.githubusercontent.com/92938944/226065395-8886e981-bb55-4980-bca4-3c0c18843b75.png).

### Understanding the data
The data was in a csv format and it was loaded into excel.  On the first glance some players names had special characters

OVA: Players overall analysis was in a different data type
![Screenshot](https://user-images.githubusercontent.com/92938944/226066333-38b1229c-2bb9-440e-8bc7-cd12d826c4ef.png)
POT: Players potential was in a different data type
Height: Players height was cm, inches and feet
Weight: Players weight in kg
Value, Wage & Release clause were not standardized and had differnt values such as M and K
 
 #### ool and Functions Used
 After loading the dataset into EXCEL here are some steps carried out:
 
 1. Using 'find and replace' function to remove on printable characters in the names 
 
 ![Screenshot (47)](https://user-images.githubusercontent.com/92938944/226068328-de51910d-e38c-4a38-b44d-9bdfdb5b5ad2.png) 
 
 2. Using the Trim function to remove excess space
 3. Creating new columns where numerical data ending with M was assigned 10000000, data ending with K was assigned 1000 and others were assigned the value of 1
 4. Using 'find and replace' function to remove 'Euro' signs and letters M and K from Value, Wage, Release_Clause and Hits. Then changing their data types to decimal 
    numbers. Multiplying these columns by their corresponding conditional columns to give actual value.
 5. Converting Height and weight columns containing two different measures to single measures using some metric conversion methods.
     
![Screenshot (48)](https://user-images.githubusercontent.com/92938944/226068414-3a67dae0-e7f8-4dd7-adde-5f7860c7439b.png)

In conclusion, data cleaning is one of the most important tasks in data analysis .

Thank you for your time as you explore the files uploaded.


 
 








