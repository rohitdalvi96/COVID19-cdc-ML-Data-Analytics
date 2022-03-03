# COVID19-cdc-ML-Data-Analytics
This homework focuses on data understanding and preparation for a particular problem and dataset. The data comes from the Centers for Disease Control and Prevention (CDC: https://covid.cdc.gov/covid-data-tracker/). CDC is a USA health protection agency and is in charge of collecting data about the COVID-19 pandemic, and in particular, tracking cases, deaths, and trends of COVID-19 in the United States. CDC collects and makes public deidentified individual-case data on a daily basis, submitted using standardized case reporting forms. In this analysis, we focus on using the data collected by CDC to build a data analytics solution for death risk prediction. CDC collects demographic characteristics, exposure history, disease severity indicators and outcomes, clinical data, laboratory diagnostic test results, and comorbidities. It also includes information on whether the individual survived or not.
The dataset we work with is a sample of the public data released by CDC, where the outcome for the target feature death_yn is known (i.e., either 'yes' or 'no'): https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf
(1) Prepare a data quality report for your CSV file. 
- Checked how many rows and columns your CSV has.
- Printed the first and the last 5 rows.
- Converted the features to their appropriate data types (e.g., decide which features are more appropriate as continuous and which ones as categorical types). 
- Looked for duplicate rows and columns. Consider whether it makes sense to keep them or drop them.
- Looked for constant columns. Consider whether it makes sense to keep them or drop them.
- Saved updated/cleaned data frame to a new csv file.

For the updated CSV and data frame (after column/row removal):
- Prepared a table with descriptive statistics for all the continuous features.
- Prepared a table with descriptive statistics for all the categorical features.
- Plot histograms for all the continuous features.
- Plot box plots for all the continuous features.
- Plot bar plots for all the categorical features.
- Discussed initial findings.
- Saved the initial discussion of my findings into a single data quality report PDF file. The PDF report focuses on the key issues identified in the data and potential strategies to handle them.
(2). Prepare a data quality plan for the cleaned CSV file.
- Marked down all the features where there are potential problems or data quality issues.
- Proposed solutions to deal with the problems identified. Explained why I chose one solution over potentially many other.
- Applied solutions to obtain a new CSV file where the identified data quality issues were addressed. 
- Saved the new CSV file with a self-explanatory name. 
- Saved the data quality plan to a single PDF file.
(3). Exploring relationships between feature pairs:
- Choosen a subset of features you find promising and plot pairwise feature interactions (e.g., continuous-continuous feature plot or continuous-categorical plots or correlation plots). 
- Discussed my findings from the plots above. Found features or feature combinations that are indicative of the target outcome. Explained in plain words the story of findings so far.
(4). Transform, extend or combine the existing features to create a few new features (at least 3) with the aim to better capture the problem domain and the target outcome. Justify the steps and choices you are making. Add these features to your clean dataset and save it as a CSV file with a self explanatory name.

