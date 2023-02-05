# Same-sex-sociosexual-behaviour-is-widespread-and-heritable-in-male-rhesus-macaques
## Accessing data, code and results

Download the main zip file containing all data and code needed to reproduce results from [here](https://mega.nz/file/DvZw1I5Y#vbmBd8JopYOFbsPS4MnPpL-JBMkSc6A1QnqKkqR7VtQ). Please note that this a large file (18.8GB), due to the storage of MCMC GLMM models as R objects. 

Separate download links are also available for supplementary video files:

[Supplementary Video 1](https://mega.nz/file/a2oEhS7K#4XNej97UtKwMEsHwbgCi4RW0aYH2J7oPOToXDGI3AvE)

[Supplementary Video 2](https://mega.nz/file/K6Y2zCLB#De18VH_h7ifot41c0FrlKF1E4MtWZfX6EQxDg-CVfpA)

[Supplementary Video 3](https://mega.nz/file/OnxEDRhS#pgGEG5G-I6WAbPUx7DOnNRvh1rrHhThpzMz4Bv1-wDI)

[Supplementary Video 4](https://mega.nz/file/OzBHxBZC#KzG0PLU5JgK64T8RdTC9IG8N9NdtVwUgSXVC1INpJpU)



Main zip file contents: 

(1) Three .pdf files displaying the figures which appear in the manuscript. 

(2) The supplementary figure, table and video files which are indexed numerically and thus referenced to throughout the manuscript.

(3) A .doc file ('SupplementaryInformation') that provides further descriptions for the 30 supplementary data files.

(4) Data reproducibility zip, which contains all raw data, code and results. Steps to perform analysis are provided in the R script file ‘RhesusPipeline.R’. Analysis is performed in three stages: first the assembling of count data, second the running of Bayesian models, and finally the collation of posterior distributions of variance and further results. The Datareproducibility zip file contains three directories: scripts are found in ‘Code’, pipeline data in ‘Use_Data’, models are stored in RData. Analysis can be run using relative working directory paths out of the ‘Code’ directory using the respective R, Python and bash scripts. We have also provided our model results in full as stored R data files, with further code templates for parallelised Bayesian model fitting for each bivariate model and additional script templates for stitching chains together after fitting (see script notes in RhesusPipeline.R for details). 

