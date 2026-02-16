#### Task Background

The main requirement for this task was to create a Data Warehouse solution and a Machine Learning implementation for a specific use case. The deliverables for this task included a Data Warehouse (Designed using a Star Schema), SQL queries to build the warehouse system, a Python script for the machine learning implementation, and a list of reporting queries based on the requirements.


### Business Purpose

This project supports a staffing and temporary cover operations scenario by enabling data-driven decision-making.

It is designed to:

* Analyse session and staffing request patterns
* Identify cover demand across:

  * Quarters
  * Council types
  * Demographic groups
  * Appointment systems
* Predict the most likely cover role required

These insights help improve:

* Workforce planning
* Demand forecasting
* Speed of staffing decisions
* Operational reporting and oversight

### ERD for the Data Warehouse Design

For this step, a Star Schema was designed based on the project requirement. Fact and dimensional modelling were done on the basis of the data present and the requirements of the project. [Link](ERD_001204526_Group_11.pdf)

### DDL to create the DW tables

After designing the fact and dimension tables, the tables were created in the data warehouse using the following scripts. [Link](DWH_Table_AND_Sequences_Creation_DDL.sql)

### Loading Data into the Warehouse

Once the database objects were created, the data was cleansed and loaded into the data warehouse system. [Link](Loading_Data_To_Warehouse.sql)

### Machine Learning Implementation using Decision Tree Classifier

A decision tree classifier was used to perform the prediction on the type of covers. [Link](COMP-1848_Decision_Tree_001204526.ipynb)

### Reporting Queries

Basic reporting on the data from the data warehouse was done to extract some information. [Link](GroupTaskQuries.sql)
