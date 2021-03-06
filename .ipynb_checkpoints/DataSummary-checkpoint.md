# Data Summary
## Accounts
### Frequency of Issuance of Statements
Values:

| Frequency | Occurrences |
| --- | --- |
| issuance after transaction | 93 |
| monthly issuance | 4167 |
| weekly issuance | 240 |

![](images/DU/account_frequencies_occurences.png)
  
### District id

Some districts have much more registered accounts then others, particularly the district with id 1


![](images/DU/account_district_id_occurences.png)

The avarage of accounts per district is 58, this are the only 9 districts with more then 58 accounts

| district_id | occurences | 
| --- | --- |
|1 | 554 |
|5 | 65 |
|46 | 59 |
|54 | 128 |
|64 | 92 |
|68 | 83 |
|70 | 152 |
|72 | 88 |
|74 | 135 |

### Date *of creation*

![](images/DU/account_month_of_creation_per_year.png)

### Date and Frequency

![](images/DU/account_frequency_by_year.png)
![](images/DU/account_frequency_iat_by_year.png)
![](images/DU/account_frequency_wi_by_year.png)
![](images/DU/account_frequency_wi_by_month_by_year.png)
![](images/DU/account_frequency_mi_by_month_by_year.png)
![](images/DU/account_frequency_iat_by_month_by_year.png)

## Client
### Sex
| Men | Women |
| --- | --- |
| 2724 | 2645 | 

### Age
Avarage: 44.802


![](images/DU/client_age.png)

### Age by District
![](images/DU/client_age_by_district.png)


## Disposition
### Type
| OWNER | DISPONENT |
| --- | --- |
| 4500 | 869 | 
![](images/DU/disposition_type.png)


## District Data
![](images/DU/districts_inhabitants.png)

![](images/DU/districts_inhabitants.png) ![](images/DU/districts_urbanization.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_employement95.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_employement96.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_average_salary.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_enterpreneurs.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_average_salary.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_average_salary.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_average_salary.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_crime95.png)
![](images/DU/districts_inhabitants.png) ![](images/DU/districts_crime96.png)


## Loan

| Field | Avarage |
| --- | --- |
| amount | 145308.621951 |
| payments | 4150.932927 |

![](images/DU/loan_status.png)
![](images/DU/loan_durations.png)

## Transaction
### 
|  |  |
| --- | --- |
| credit | 159468 |
| withdrawal | 232093 |
| withdrawal in cash | 5124 |

![](images/DU/transaction_type.png)

# Relations on final loanDataset
### Has the same district account and client
![](images/DU/loan_fail_distric_same.png) ![](images/DU/loan_success_distric_same.png)
    

![](images/DU/district_success_vs_loan.png)
