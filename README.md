![image](https://github.com/oladeeayo/Car-Insurance-Report/assets/13979269/2f8c84f3-f776-4d4e-8022-7defb9a2044d)# Car-Insurance-Report
This report is a dashboard on car insurance claims by various individuals. It detailed claims frequency, claims amount, car brands, and age range of insurance claimers among other things.

## Introduction
Car Insurance is an insurance policy where the insurer (insurance company) protects the car of the insured (you) in the event of an accident, theft, loss, or damage. This protection is valid upon paying an agreed annual premium according to what is outlined in your policy.

This dataset presents various data from a car insurance company to highlight various information on their customers. The dataset comprises various details like
⏬⏬⏬

**Data Dictionary**
.
├── id                                            : Customer's record ID
├── birthdate                                     : Customer's Birthday (mm/dd/yyyy)
├── marital_status                                : Customer's maritla status
├── car_use                                       : The reason of having a car: private, commercial
├── gender                                        : Customer's gender 
├── kids_driving                                  : No of Customers using the same car
├── parent                                        : Is Customer a parent?
├── education                                     : Customer's education level 
├── car_make                                      : Car manufacturer
├── car_model                                     : Car's model 
├── car_color                                     : Car's color
├── car_year                                      : The year that the car is in manufacture
├── claim_freq                                    : How many time do customer claim insurance 
├── coverage_zone                                 : What is the coverage zone
├── claim_amt                                     : Claim amount
└── household_income                              : Household income 


## Data Cleaning

A few of the dataset was cleaned for better representation, the birthrate column was converted from (mm/dd/yyyy) to (dd/mm/yyyy) to allow proper representation of the claimant's birthdate.

Also, a new column called age and age range was created to know the current claimant's age and sub-represented in age range categories like 20 - 29, 30 - 39, 40 - 49, 50 - 59, 60 - 69 and 70 -79




