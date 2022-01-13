# NCSL-project
# Author: Siwei (Lily) Mao

# Data
  The source of the data is the National Conference of State Legislatures Database, which contains recently enacted statewide sentencing and corrections legislation.
  Prior to performing the data analysis in this repository, I built a web-scraper to obtain the legislation data, and reorganized the data according to states, bill number, law name, author, and date of last action. As many of the laws touch on more than one topic, I coded the topics as binary variables (each law has a value of "1" for every topic it covers). I saved the data as an Excel file, a copy of which is also uploaded to the repository. Thus, we only need to use the read.xlsx() function to import the data frame. 
  
# Packages needed
library(ggplot2)
library(tidyverse)
library(tidyr)
library(openxlsx)
library(dplyr)
library(forcats)

# Files in the repository
[Tidy Data frame](NCSL-project/project_data_updated.xlsx)
[Data Analysis with code and plots](NCSL-project.Rmd)
[Folder containing all the plots and files generated](NCSL-project/NCSL-project_files)
  

