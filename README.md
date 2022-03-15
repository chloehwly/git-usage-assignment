# git-usage-assignment
Computing Skills Practical Assignment HT 2022
This repository contains an analysis of the average monthly rainfall in Melbourne and Oxford from 1855 to 2015.
To run this analysis, follow a two step process:

1. Combine rainfall data of Melbourne & Oxford into a single dataset, using the following command:
```
Rscript src/combine-data.R
```
2. Next, run the analysis on average rainfall data using the following command:
```
Rscript src/make-plot.R
```
The input data for step 1 is in `data/raw-data` and the input data for step 2 is in `data`. 
The results are in `out`.
