# BME580_FinalProject

This is our repository for our BME 580 project investigating the relationships between race and hospital readmission following hip fracture surgery. Our data is being housed in Box and must be downloaded locally in order to run the rmd files. Note the file path in the rmd files must be adjusted to your local file path once you have downloaded the data. 

## Data_Cleaning.Rmd

This RMD file takes the original raw NSQIP data frame and drops a number of columns, renames our response variable and splits the data into training and test sets which are exported as CSV files. Our original data set included 383 variables. 225 were original variables while the rest had either been encoded or engineered from existing variables. The first part of our project was coming through every variable and dropping the many variables that were either irrelevant to our modelling task, redundant or would cause leakage (169 total columns). We used our domain expertise and logic to identify these, keeping in mind that this database is a national repository of information and not designed to this modelling task at end.  Next we went through every encoded column left and documented how it had been encoded or engineered (levels, binary v. onehot etc.) and where it originally came from. We also indicated what type of information it contained, specifically, information relevant to pre-operative health, post-operative health and complications, demographics, or peri-operative information. Finally we split our simplified data set into training and test sets for further exlploration.






