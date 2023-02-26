# U.S Medical Insurance Costs Analyze Project
In this project, a CSV file with medical insurance costs will be investigated using Python fundamentals. The goal with this project will be to analyze various attributes within **insurance.csv** to learn more about the patient information in the file and gain insight into potential use cases for the dataset.

> This project is from [Codecademy](https://www.codecademy.com/career-journey/data-scientist-aly/path/dsalycj-22-data-science-foundations/track/dsalycj-22-portfolio-project-u-s-medical-insurance) and dataset from [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## Getting Started

`insurance.csv` contains the following columns:

- Patient Age
- Patient Sex
- Patient BMI
- Patient Number of Children
- Patient Smoking Status
- Patient U.S Geopraphical Region
- Patient Yearly Medical Insurance Cost

There are no signs of missing data. To store this information, seven empty lists will be created hold each individual column of data from insurance.csv.

### What is to be done in this project?

There are many aspects of the data that could be looked into. The following operations will be implemented:

- find average age of the patients
- return the number of males vs. females counted in the dataset
- find geographical location of the patients
- return the average yearly medical charges of the patients
- return the effect of smoking on insurance costs
- return total insurance charges by age
- creating a dictionary that contains all patient information

To perform these inspections, a class called `PatientsInfo` has been built out which contains fives methods:

- `analyze_ages()`
- `analyze_sexes()`
- `unique_regions()`
- `average_charges()`
- `smoking_effects()`
- `analyze_charges_by_age()`
- `create_dictionary()`
