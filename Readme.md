## Medical Billing & Healthcare data analysis

This repository is part of a project portfolio designed to showcase data analytics and modeling capabilities. 


### Project overview

This project focuses on analyzing hospital-generated healthcare data to evaluate insurance coverage, patient costs, diagnosis, medical procedures and medications. By structuring and modeling medical data, it was possible to create a visual report to facilitate data interpretation. 

The analysis integrates standard medical coding systems, including:

- CPT (Current Procedural Terminology)

- ICD-10 (International Classification of Diseases)

- HCPCS (Healthcare Common Procedure Coding System)

### Raw data origin
The dataset to create this project was found here: 
<https://www.kaggle.com/datasets/devp1866/noisy-medical-document-images-ocr>


### Raw data treatment
The raw data consists of a CSV file JSON data divided into several columns. Using Javascript/Node, I read the file, joined the rows, fixed some errors and created a new JSON file I uploaded to Excel. 
Using Excel, I split the data into multiple tables that were uploaded to Power BI. 

### Reports generated

#### Costs related to diagnosis
This report shows some medical conditions \(Diabetes Mellitus, Osteoarthritis, etc.\), the number of times this condition required hospital care, the amount of expenses they cause, and the amount of money money covered by the insurance company.

![DiagnosisGif](https://github.com/DanielaGProjects/Healthcare_Power_BI/blob/main/Gifs/DiagnosisGif.gif)


#### Correlation with age
This view shows how age and diseases are correlated, graps show the highest numbers in red and the lowest numbers in blue. 
![AgeCorrelation](https://github.com/DanielaGProjects/Healthcare_Power_BI/blob/main/Gifs/PatientsGif.gif)


#### Hospitals Data
This report aims to demonstrate the number of cases received by hospitals, the amount of money they charge, and the amount that the insurance company must cover.
![HospitalsData](https://github.com/DanielaGProjects/Healthcare_Power_BI/blob/main/Gifs/HospitalsGif.gif)

