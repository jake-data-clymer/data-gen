##### Synthetic Data Generator

This Streamlit application is designed to create realistic, synthetic data for Salesforce objects, aiding in development, testing, and training without using real customer data. Data is generated used the Python library, **Faker**: https://faker.readthedocs.io/en/master/

##### How It Works

**Select Salesforce Objects:**
- Choose one or more Salesforce objects from: **Accounts, Opportunities, Users, Quotes, and Orders**.
 
**Specify Record Count:**
- Input the number of records you want to generate.
- Limited to **10,000 records** per object.
 
**Data Generation:**
- For objects **Opportunities, Quotes, and/or Orders**, the application intelligently creates dependencies based on **Account IDs**,**Opportunities IDs**, and **Quote IDs** ensuring realistic data relationships.