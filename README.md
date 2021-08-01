# al-gore-ithms
### Overview
A CSCI 1951A final project investigating the relationship between the usage of health-related words in U.S. President State of the Union Addresses (SOTUA) and the U.S. government's annual percentage spend on the Health and Human Services department.  

### Datasets
SOTUA were webscraped from the [UCSB American Presidency Project](https://www.presidency.ucsb.edu/documents/presidential-documents-archive-guidebook/annual-messages-congress-the-state-the-union). The Health and Human Services department annual spend data was dervied from historical tables from [the Office of Management and Budget](https://www.whitehouse.gov/omb/historical-tables/). For additional information on the data collection process and dataset commentary, please refer to the [data deliverable document](/data-deliverable.md).

### Analysis
The following questions were asked during the exploratory analysis phase:  
* Can we extract a health-related dimension using topic modelling (Latent Dirichlet Allocation)?  
* Is there a difference in the distributions of the proportion of health-reated words (for Republicans and Democrats) between a president's 1st, 2nd, 3rd, and 4th SOTUA? Ran Friedman's test on Republican and Democrat speeches.
* Is there a relationship between frequency of health-related words and percentage spend on the health department? Ran linear regressions by clusters (pre-Clinton and post-Clinton) and for each president.

For results of these analyses, please refer to [the Collab notebook](/final_project.ipynb). For the final presentation, the group chose to focus on (method 1) and (method 2). Final conclusions are shown in the [final presentation slides]().

