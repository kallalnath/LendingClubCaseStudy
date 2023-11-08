# LENDING CLUB CASE STUDY
> Exploring data provided by a lending club to provide insights, which would be helpful in analysing risk factors before lending loan to the customers. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A lending club looking out to cut it's financial losses by avoiding borrowers who are most likely to default, and increase business by lending borrowers who are most likely to repay.
- Aim is to find out patterns of defaulting customers, so that the risk of financial loss can be reduced in the future. Also, identify patterns of borrowers who are most likely to pay 
- A data set containing information about past loan applicants and whether they ‘defaulted’ or not . 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Observations
    - Around 14% of the borrowers during the period 2007 – 2011 turned out to be defaulters.
    - Borrowers frequently opt for loan between 5%-7% and 10% -15% interest rate
    - More than 50% of the loans granted in 5 years were with high grade ‘A’, ‘B’ and ‘C’.
    - Borrowers in rental house or mortgaged house are more interested in acquiring a loan.
    - Majority of the borrowers have no record of Public Recorded Bankruptcy. 
    - Majority of the borrowers have very large debt compared to their income, concentrated mostly in the 10-20 DTI ratio.
    - Majority of borrowers have fairly low annual income as compared to rest who are less in numbers.
    - Majority of the loans were taken for debt consolidation followed by credit card. Such borrowers already have running debt to cover. And they take further loan to pay for their credit card outstanding.


- Major Driving factor which can be used to predict the chance of defaulting and hence avoiding Credit Loss:
    1. DTI 
    2. Grades
    3. Verification Status
    4. Annual income
    5. Public record bankruptcies
    6. Interest rate
    7. Purpose


-  Defaulters are most likely to have following patterns
    1. From large urban cities like California, New York, Texas, Florida etc. 
    2. Annual income in the range 50000-100000.
    3. Borrowers having Public Recorded Bankruptcy.
    4. Borrowers with least sub grades like E,F,G which indicates high risk.
    5. Loan purpose is debt consolidation or credit card.
    6. Borrowers having working experience of more than 10 years.
    7. Borrowers with Debt-to-Income ratio greater than 13
    8. Interest rate higher than 12
    9. Paid interest exceeding paid principle
    10.Revolving Utilization is more than 50%
    11.Loan repayment duration is less than 3 years


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy   - 1.24.3
- python  - 3.11.4
- seaborn - 0.13.0
- pandas  - 1.5.3
- plotly  - 5.17.0
- matplotlib - 3.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on [Lending club Case study by upgrad](https://learn.upgrad.com/course/4705/segment/42284/254159/776531/3902171).


## Contact
Created by [https://github.com/kallalnath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->