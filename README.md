# DATA2LIFT Opportunity Youth Analysis
This repo is a shared space for data analysis and visualization tools related to opportunity youth. This repo is a part of QSIDE's [DATA2LIFT initiative.](http://qsideinstitute.org/data2lift/) 

## Current Action Items (Due Tues. April 9th, 2024):
1. Create a contingency table containing chi-squared test results for sex/race/age in the individual-level foster care dataset. [Here](https://www.stratascratch.com/blog/chi-square-test-in-python-a-technical-guide/) is an example guide.
2. Create a figure showing the sex breakdown by race. This figure should have 9 columns of equal width (one column for each race/ethnicity category and one for the whole population). columns should all be the same height, with male + female categories adding up to 100\%.
3. Add reproducible code to this repo.
  - Code should be commented well enough for another team member to understand.
  - Code should be written so that changes are possible, especially to the plot style.  

## Opportunity Youth Data

Some of the data used in this project are sensitive because they document individual experiences within the foster care system. The National Data Archive on Child Abuse and Neglect (NDACAN) has granted the researchers on this project permission to use these data to better understand the population of youth in foster care. 

### Working with the Individual-Level Foster Care Dataset

1. **Request Access to the Data:**
   - Open the PDF file `LastName FirstName 2024-03-13.pdf` in the `RawData` folder.
   - Follow the instructions at the top of the PDF to request access to the individual-level foster data from the National Data Archive on Child Abuse and Neglect (NDACAN). Please note that this process can take several days.

2. **Prepare the Data:**
   - Once you receive the data from NDACAN, download the data to your local machine and unzip the data folder.

3. **Store the Data Securely:**
   - Move the unzipped data folder to `RawData/SensitiveData` to keep the sensitive data separate from other project files.
   - The `SensitiveData` folder is included in the `.gitignore` file to prevent accidental uploading of sensitive data to this public repository. However, always exercise caution to ensure that the individual-level foster care dataset is never inadvertently added to this repository.

### Usage Guidelines

- **Data Security:** Always store sensitive data in a secure location and follow best practices for data privacy and protection.
- **Ethical Considerations:** Use the data responsibly and ethically, respecting the privacy and confidentiality of individuals represented in the dataset.
- **Sharing Results:** When sharing research findings, ensure that no individual-level data is disclosed and that all results are presented in an aggregated and anonymized form.
