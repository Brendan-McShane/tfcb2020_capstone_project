# tfcb2020_capstone_project
Brendan McShane
Capstone project for tfcb2020


This directory is organized such that source data files both in compressed and uncompressed form are in the "data" directory while the Jupyter 
notebook and R markdown files are in the parent directory.


For this project, I used the glaucoma data set (see below for citation). There are three .csv files where two are subsets of the other that were 
used for the machine learning portion of the original paper. After researching what the headings meant, I renamed the variables in ds_whole.csv 
to be more descriptive biologically. I wasn't clear to me from my initial reading of the paper from which the data were sourced what each header
actually meant, so I has to find some other sources online to help. I would recommend the authors describe this more obviously in the depo.

## Questions

1) Are the continuous variables within the total data set normally distributed? If not, are they normally distributed after subsetting by
 disease state? 

2) After PCA, how many dimensions are necessary to account for at least 95% of the variance within the data?

3) Which continuous variables are the most correlated, and to what extent? Do these correlations change after subsetting by disease state?
	

## Reproducibility

Hopefully between the comments in the code and the README, my analyses are easy to follow through and reproduce. I'll say that the original authors do a reasonable job describing the dataset and stating which models they use to compare to; however, I could not find the actual code they used for their model. Whether this is my own failing to understand/interpret their work or them not actually making it clear is not apparent to me.

## Citation
Kim, Seongjae; Cho, Kyung Jin; Oh, Sejong (2018), Data from: Development of machine learning models for diagnosis of glaucoma, Dryad, Dataset,
https://doi.org/10.5061/dryad.q6ft5
