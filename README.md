#### Project Title: Predictive Analytics for Enhanced Customer Experience and Risk Management in Insurance

#### Project Overview:
- Our aim with this project is to develop a comprehensive framework for multi-predictive modeling using various statistical and machine learning techniques. The primary objective is to build and compare multiple prediction models, each tailored to understand different aspects of the dataset. We will conduct a detailed exploratory data analysis (EDA) to uncover patterns, detect anomalies, and gain insights that will inform model development. The project seeks to enhance forecasting accuracy and provide robust decision-making tools across different scenarios through the integration of diverse modeling approaches.


##### Objectives:
- The purpose of this project is to determine which policyholders, based on their policy interaction history, policy details and claim history are likely to have a favorable experience.The goal is be able to make a model that can actively proactively provide individualized services.
- The second objective of this project to use predictive analytics to predict total claims.
- The reason we are doing this to see explore different insight to fraud mechanism

#### Datasets: 
''' 
Link:
| Variable                         | Description                          |
|----------------------------------|--------------------------------------|
| months_as_customer               | Number of months as a customer       |
| age                              | Age of the insured                   |
| policy_number                    | Unique policy number                 |
| policy_bind_date                 | Date when the policy was bound       |
| policy_state                     | State where the policy was issued    |
| policy_csl                       | Combined Single Limit policy detail  |
| policy_deductable                | Deductible amount of the policy      |
| policy_annual_premium            | Annual premium for the policy        |
| umbrella_limit                   | Limit on the umbrella coverage       |
| insured_zip                      | ZIP code of the insured              |
| insured_sex                      | Sex of the insured                   |
| insured_education_level          | Education level of the insured       |
| insured_occupation               | Occupation of the insured            |
| insured_hobbies                  | Hobbies of the insured               |
| insured_relationship             | Relationship of the insured          |
| capital-gains                    | Capital gains reported               |
| capital-loss                     | Capital losses reported              |
| incident_date                    | Date of the incident                 |
| incident_type                    | Type of incident                     |
| collision_type                   | Type of collision                    |
| incident_severity                | Severity of the incident             |
| authorities_contacted            | Authorities contacted post-incident  |
| incident_state                   | State where the incident occurred    |
| incident_city                    | City where the incident occurred     |
| incident_location                | Specific location of the incident    |
| incident_hour_of_the_day         | Hour when the incident occurred      |
| number_of_vehicles_involved      | Number of vehicles involved          |
| property_damage                  | Property damage occurred             |
| bodily_injuries                  | Bodily injuries occurred             |
| witnesses                        | Number of witnesses present          |
| police_report_available          | Availability of a police report      |
| total_claim_amount               | Total amount claimed                 |
| injury_claim                     | Claim amount for injuries            |
| property_claim                   | Claim amount for property damage     |
| vehicle_claim                    | Claim amount for vehicle damage      |
| auto_make                        | Make of the vehicle                  |
| auto_model                       | Model of the vehicle                 |
| auto_year                        | Year of the vehicle                  |
| fraud_reported                   | Whether fraud was reported           |
| _c39                             | Placeholder for additional data      |

#### Project Folder Structure:
your-repository-name/
│
├── data/
│   └── insurance_claims.csv       # Dataset file
│
├── task1/
│   └── task1-datacleaning_eda.ipynb  # Data cleaning and exploratory data analysis
│
├── task2/
│   └── featureengineering_clusteranalysis.ipynb  # Feature engineering and cluster analysis
│
├── task3/
│   └── featureengineering_predictivemodeling.ipynb  # Continuation of feature engineering and predictive modeling
│
├── task4/
│   └── predicting_fraud_claims.ipynb  # Notebook for predicting fraud claims
│
└── README.md                          # README file for the repository



  

  
