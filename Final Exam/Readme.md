# FINAL EXAM

In this final challenge, you will put into practice some of the key principles and techniques you have learned in the course.

The challenge does not include specific step-by-step instructions, so you must interpret the requirements and perform the necessary tasks to build, test, and optimize your model. After you have created your model, you are required to enter the predicted labels for a test dataset that is provided in the lab files for this course so that your model's performance can be graded. The challenge accounts for 50% of your overall grade.

## Challenge Overview
In 1998, the Adventure Works Cycles company collected a large volume of data about their existing customers, including demographic features and information about purchases they have made. The company is particularly interested in analyzing customer data to determine any apparent relationships between demographic features known about the customers and the likelihood of a customer purchasing a bike. Additionally, the analysis should endeavor to determine whether a customer's average monthly spend with the company can be predicted from known customer characteristics.

In this project, you must tackle three challenges:

Challenge 1: Explore the data and gain some insights into Adventure Works customer characteristics and purchasing behavior.
Challenge 2: Build a classification model to predict customer purchasing behavior.
Challenge 3: Build a regression model to predict customer purchasing behavior.
You can explore the customer data using tools of your choice. Potential tools that you could use include:

- Microsoft Excel
- R
- Python
- Microsoft Azure Machine Learning

This data consists of three files, containing data that was collected on January 1st 1998.

Dataset is included in the repo.

### AdvWorksCusts.csv
Customer demographic data consisting of the following fields:

- CustomerID (integer): A unique customer identifier.
- Title (string): The customer's formal title (Mr, Mrs, Ms, Miss Dr, etc.)
- FirstName (string): The customer's first name.
- MiddleName (string): The customer's middle name.
- LastName (string): The customer's last name.
- Suffix (string): A suffix for the customer name (Jr, Sr, etc.)
- AddressLine1 (string): The first line of the customer's home address.
- AddressLine2 (string): The second line of the customer's home address.
- City (string): The city where the customer lives.
- StateProvince (string): The state or province where the customer lives.
- CountryRegion (string): The country or region where the customer lives.
- PostalCode (string): The postal code for the customer's address.
- PhoneNumber (string): The customer's telephone number.
- BirthDate (date): The customer's date of birth in the format YYYY-MM-DD.
- Education (string): The maximum level of education achieved by the customer:
  * Partial High School
  * High School
  * Partial College
  * Bachelors
  * Graduate Degree
- Occupation (string): The type of job in which the customer is employed:
  * Manual
  * Skilled Manual
  * Clerical
  * Management
  * Professional
- Gender (string): The customer's gender (for example, M for male, F for female, etc.)
- MaritalStatus (string): Whether the customer is married (M) or single (S).
- HomeOwnerFlag (integer): A Boolean flag indicating whether the customer owns their own home (1) or not (0).
- NumberCarsOwned (integer): The number of cars owned by the customer.
- NumberChildrenAtHome (integer): The number of children the customer has who live at home.
- TotalChildren (integer): The total number of children the customer has.
- YearlyIncome (decimal): The annual income of the customer.

### AW_AveMonthSpend.csv
Sales data for existing customers, consisting of the following fields:

- CustomerID (integer): The unique identifier for the customer.
- AveMonthSpend (decimal): The amount of money the customer spends with Adventure Works Cycles on average each month.

### AW_BikeBuyer.csv
Sales data for existing customers, consisting of the following fields:

- CustomerID (integer): The unique identifier for the customer.
- BikeBuyer (integer): A Boolean flag indicating whether a customer has previously purchased a bike (1) or not (0).


# Challenge : Classification
 Marcar esta página
You have explored and analyzed customer data collected by the Adventure Works Cycles company. Now you should be ready to apply what you have learned about the data to building, testing, and optimizing a predictive machine learning model.

Specifically, you must use any combination of Azure Machine Learning, R or Python to create a classification model that predicts whether or not a new customer will buy a bike.

## Challenge Instructions
To complete this challenge:

Use the Adventure Works Cycles customer data you worked with in challenge 1 to create a classification model that predicts whether or not a customer will purchase a bike. The model should predict bike purchasing for new customers for whom no information about average monthly spend or previous bike purchases is available.
Download the test data. This data includes customer features but does not include bike purchasing or average monthly spend values.
Use your model to predict the corresponding test dataset. Don't forget to apply what you've learned throughout this course.
Go to the next page to check how well your prediction against the actual result.

# Challenge : Regression
 Marcar esta página
Now, you must use any combination of Azure Machine Learning, R or Python to create a regression model that predicts the average monthly spend of a new customers.

## Challenge Instructions
To complete this challenge:

Use the Adventure Works Cycles customer data you worked with in challenge 1 and 2 to create a regression model that predicts a customer's average monthly spend. The model should predict average monthly spend for new customers for whom no information about average monthly spend or previous bike purchases is available.
Download the test data. This is the same test data that you have used in classification challenge. This data includes customer features but does not include bike purchasing or average monthly spend values.
Use your model to predict on the corresponding test dataset. Don't forget to apply what you've learned throughout this course.
Go to the next page to check how well your prediction against the actual result.
