# Food Claims Process (Power BI)
This project served as a practical examination for my [Data Analyst Associate Certification](https://www.datacamp.com/certificate/DAA0011458595795) with DataCamp. My objective was to excel in the certification by demonstrating my skills in data analysis. Leveraging Power BI, I engaged in the project to analyze and interpret data effectively.

# Background 
Vivendo, a prominent fast food chain in Brazil boasting over 200 outlets, faces a common challenge: customers frequently file claims for food poisoning. To address this issue, the legal team, operating from four different locations, manages the processing of these claims. Now, the focus is on enhancing customer service by expediting claim resolution times.

The head of the legal department has tasked us with providing a comprehensive report detailing the variations in claim closure times across each location. This analysis will shed light on areas for improvement and aid in streamlining the claims management process.

# Data
The dataset contains one row for each claim.
The dataset can be downloaded from [here](https://github.com/Man-of-principle/Food-claims-Analysis-Power-BI-/tree/main/Dataset).

| Column Name |  Criteria |
|-------------| ----------|
| claim_id | Nominal. The unique identifier of the claim. Missing values are not possible due to the database structure.|
|time_to_close| Discrete. The number of days to close the claim. Any positive value. Replace missing values with the overall median time to close.|
| claim_amount |Continuous. The initial claim requested in the currency of Brazil,rounded to 2 decimal places.Replace missing values with the overall median claim amount.|
| amount_paid |Continuous. Final amount paid. In the currency of Brazil. Roundedto 2 decimal places.Replace missing values with the overall median amount paid.|
| location | Nominal. Location of the claim, one of “RECIFE”, “SAO LUIS”,“FORTALEZA”, or “NATAL”.Remove missing values.|
|individuals_on_claim|Discrete. Number of individuals on this claim. Minimum 1 person.Replace missing value with 0.|
|linked_cases|Nominal. Whether this claim is linked to other cases. Either TRUE or FALSE.Replace missing values with FALSE.|
|cause|Nominal. Cause of the food poisoning. One of “vegetable”, “meat” or “unknown”. Replace missing values with ‘unknown’.|


**To view The Analysis Click [Here](https://github.com/Man-of-principle/Food-claims-Analysis-Power-BI-/blob/main/file/Food%20Claim%20Solutions%20.ipynb)**



