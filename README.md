# Project Name
> As an employee of a financial company specializing to disburse loans to urban customers, I am required to make a risk assessment model to help a company understand whether the loan disbursed to a customer is risky or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Overview Of The Project/Problem Statement.
  -   As an employee of a financial company specializing to disburse loans to urban customers, I am required to make a risk assessment model to help a company understand whether the loan disbursed to a customer is risky or not. 
 
- What is the background of your project?
  - A person applying for a loan, there are 2 decision taken by the company. Either the loan is accpeted or rejected. The is represented below
  
![alt text](https://github.com/hargurjeet/Lending-Club-CaseStudy/blob/main/loan_dataset.PNG)

- What is the business probem that your project is trying to solve?
  - The current exercise should help to understand the driving factors behind the loan default as loan defaults are the largest loss to lenders. How consumer attributes and loan attributes influence the tendency of default.
- What is the dataset that is being used?
  - The dataset provides has the details of the past loan applicants and whether they have ‘defaulted’ or not. The objective is to identify if the loan should be given, reduced amount to be disbursed, or the loan should not be provided.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Following features are important to consider for loan approval decision.

- Homeownership - People staying in rented and mortgage accomodation loan defaluted more than people staying in their own accomodation. The default rate on paying the installments are maximum when the home ownership is classified as 'Others'
- Purpose - Applicants have defaulted more that are taking loans for the purpose of Debt Consolidation. People taking loan for the purpose of renewable energy seems to be risky as they have defaulted on lower as well higher loan amount.
- Employement year - The median difference of defaulted loans and sucessful loan are quite high between the year 5 to 10.
- Interest Rates - The interest rate are critical. With high interest rates the chances of defualting the loan increases.
- Annaul Income level - Applicants with high annual income has not defaulted but applicants with low annual income has defualted.Applicants with median salary around 50k seems to have defaulted the most.


## Technologies Used
- Pandas - https://pandas.pydata.org/
- Matplotlib - https://matplotlib.org/stable/index.html
- Seaborn - https://seaborn.pydata.org/

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@hargurjeet] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
