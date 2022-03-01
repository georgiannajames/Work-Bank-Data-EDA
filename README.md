# Work-Bank-Data-EDA

Author: Georgiannna James

This repository was created to complete and submit Assignment Four for the course [MACS30500](https://cfss.uchicago.edu) at the University of Chicago. 

## Repository Summary

This repository is an exploration of world bank data. First, I write a function to import and tidy the world bank csv files. Next, I map this function over each dataset for every country. Finally, I create a data set called ```world_bank_data``` that includes the world bank data from every country. 

Once the data is wrangled, I perform an exploratory data analysis of the relationship between female labor participation and GDP over time.

Both the world bank data analysis and the programming excercises have been uploaded as both an RMD and an MD file for ease of viewing:

* [World Bank Exploration Rmd](./world_bank_data_EDA.Rmd)
* [World Bank Exploration Md](./world_bank_data_EDA.md)

## Data

The world bank data can be found in the repository as well as [here](https://databank.worldbank.org/home.aspx). 

 


## Required packages

The following packages are required:

```

library(tidyverse)
library(knitr)

``` 


## Useful Resources 

* [Scaling Graphs by Percent](https://thomasadventure.blog/posts/ggplot2-percentage-scale/)
