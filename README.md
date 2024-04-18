# ST421-Data-Science-Dissertation
This repo contains the code and data sets to reproduce the results in the ST421 Data Science Dissertation: Survival Analysis of Breast Cancer Patients from the METABRIC Study

## What is in this repo?

This repo contains the following files: 

### YM_ST421_RCode.Rmd

This contains all the R code to reproduce all the results given in the report. The coding was done in R and this file is an RMarkdown file so the code is divided up into chunks and plots and tables can be printed within the console. 

#### How to run

This file can be opened in R and RStudio and the code can be run sequentially all at once or selected chunks can be run as required. Note the data file must be downloaded as well to run the code (see below).

### YM_ST421_RCode.R

This is an identical code document to the above, as the RMarkdown file has been converted to an R file which can be used and run the same way. R files have less readability and usability compared to the RMarkdown file and the RMarkdown file is recommended to be downloaded  instead.

#### How to run

This file can be opened in R and RStudio and the code can be run sequentially all at once or selected chunks can be run as required. Note the data file must be downloaded as well to run the code (see below).

### METABRIC_Clinical.csv

This is the raw original data set which has been downloaded from Kaggle.com which was used in this dissertation. This file is required to be downloaded to run the code files above.

### METABRIC_Clinical_Imputed.csv

Part of the code in the R files involves performing random forest imputation. This code is in the files but takes a long time to run. So the results of performing the imputation are saved as this .csv file, which contains the subsetted 31 clinical attributes plus the new columns which are the new inputted columns where the original columns have missing data. In the code, it is possible to perform the imputation directly (although this is slow), or this .csv file can be read and the result is the same. 
