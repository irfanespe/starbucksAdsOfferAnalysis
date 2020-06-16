# Starbucks Offering Analytics
## by Irfan Septiyana Putra

## Project motivation

This project is performed to gain new insight for company development. I focused on these topics below :
1. Finding the highest completed rate offer. 
2. Inspecting customer segment who completed the most offer.

## Medium Link : https://medium.com/@irfanespe/from-e-commerce-data-to-business-insight-fd4cd4b7968

## Programming Language

This excercise is based on python programming language.

## Used Libraries

- numpy 1.18.1
- matplotlib 3.1.1
- Pandas 0.25.3
- Scikit-Learn 0.22.1
- Seaborn 0.9.0
- json 0.9.0

## Dataset

> Dataset in this project is come from starbucks. It consist of 3 dataset, there are :
**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record  

## Summary of Findings

> From the dataset given, there are two business question that can be explored more through data analysis. First problem is finding the highest completed rate among 10 offers. From data explanatory, gotten that all offers can be grouped into 3 clusters and clusters with highest completed rate contains 2 offers. Those offering has completed rate around 67.4% and 69.9% which are very high compared with the others. Those offering have similiar characteristics such as spreading in web, email, social and mobile also having discount type. Customers which completed offer 6 and 7 mostly are male with proporsion 0.58. Starbucks can optimize the offering if they gives more offer in male customers with age range 40 - 70 years old with income between 40.000 - 75.000. For women customers, it will be good if starbucks give more offering to female with age more than 50 years old and least than 70 years old, and income range 50.000 - 80.000


