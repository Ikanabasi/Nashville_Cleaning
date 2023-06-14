#DATA CLEANING AND MANIPULATION WITH PYTHON
In this project, i used python pandas and numpy to clean data i got from youtube

**IMPORTING AND READING DATA(RAW DATA)**
![Screenshot (23)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/a44b5872-140c-4aeb-8b07-5b2de5fef9a6)
I explored the data

**DROP DUPLICATES**
![Screenshot (15)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/09de5d20-a5b2-40f6-a645-e468bc8e31fa)
I checked for duplicates in the data and it returned the same number of rows and columns which means there were no duplicates.

**DROP NaN VALUES**
![Screenshot (16)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/2439d327-803e-432e-92c1-c66d379dcf22)
I dropped the null values because when i went through and explored the data i realized i couldn't work with the rows with null values so i dropped all of it.

**SPLIT PROPERTY AND OWNER ADDRESS**
![Screenshot (19)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/b3cc60b5-10ac-4fad-950d-7743e5323d97)
For property address, the street and city were in the same column, but then to make the data more readable for users or clients, i split them into different columns, i also did same for owner address.

**PUT PRICE IN DOLLARS**
![Screenshot (18)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/69091729-3436-41e0-b134-166907aed7e9)
I manipulated the data and placed a dollar sign in the numbers necessary to let anyone reading the data to understand that the prices were in dollars.

**CONVERT DATA TYPES**
![Screenshot (20)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/9e98d7ed-736f-4716-b549-899faa78373e)
Colums like YearBuilt, Bedrooms, Fullbath and Halfbath were in float format which wasnt supposed to be so so i manipulated it by converting those collumns to integers.

**EXPORT DATA(CLEAN DATA)**
![Screenshot (22)](https://github.com/Ikanabasi/Nashville_Cleaning/assets/116980575/e3e92587-5afb-4337-9e55-4780d857051d)
I exported the clean data in CSV format to my pc.



