# Autumn Assignment BIO 5023Y

Summative group assignment for module BIO 5023Y - Data Science for Biologists.

## Project description

This is a group assignment for students taking BIO 5023Y. With a csv-formatted COVID-19 linelist, use this data to create an outbreak situation report (maximum two pages) that addresses any topics or trends that are deemed relevant to inform an audience of public health and medical responders. 

Students are responsible for:

* Checking the dataset for errors or mistakes

* Check that all columns are identified with the correct variable type

* Conduct exploratory data analysis to identify topics or trends of importance

* Produce one summary figure per person in the group - each figure should be appropriate for the intended audience and may contain annotations or labels to aid explanation. Any requisite summary text to provide context or aid understanding should be included in the final report

* Combine all figures with explanatory text into a short (2-page maximum) report compiled with Rmarkdown to be presented at a weekly situation update meeting attended by public health officials and medical responders

## Data

The data is a fake version of a covid linelist a data format for collecting case numbers and information for epidemiology. This data was originally provided by Batra, Neale et al. (2021), The Epidemiologist R Handbook. https://zenodo.org/badge/doi/10.5281/zenodo.4752646.svg

### Variables

| Variable| Definition|
|----|----|
| PID| Personal Identification - a unique identifier code assigned to each person that allows case tracking while preserving patient data confidentiality|
| reprt_creationdt_FALSE| Date of entry for case|
| case_dob_FALSE| Date of birth|
| case_age| Age of person|
| case_gender| Gender of person|
| case_race| U.S. census bureau social definition of race for person|
| case_eth| U.S. census bureau social definition of ethnicity for person|
| case_zip| zip code of person's known address|
| Contact_id| Symptomatic status of person|
| sym_startdt_FALSE| Date of first symptoms (if known)|
| sym_fever| Person has/had fever symptoms
| sym_myalgia| Person has/had myalgia symptoms
| sym_loststastesmell| Person has/had a loss of taste or smell
| sym_sorethroat| Person has/had a sore throat
| sym_headache| Person has/had a headache
| sym_resolveddt_FALSE| Person symptoms now resolved
| contact_household| Person has household contacts (someone who stays more than 5 nights per week)
| hospitalized| Person admitted to hospital
| hosp_admidt_FALSE| Date of hospital admission
| hosp_dischdt_FALSE| Date of hospital discharge
| died| Person died Y/N
| died_covid| Covid on death certificate Y/N
| died_dt_FALSE| Date of death
| confirmed_case| Confirmed case of COVID-19
| pos_sampledt_FALSE| Date of positive PCR test







