# Same-sex-sociosexual-behaviour-is-widespread-and-heritable-in-male-rhesus-macaques
## Accessing data, code and results

Download the password-protected zip file containing all data and code needed to reproduce results from [here](https://google.com) (password available on request).

Contents: 

(1) Three .pdf files displaying the figures which appear in the manuscript. 

(2) The supplementary data files indexed 1-29 which are referred to throughout the manuscript. These include data tables, photo panels and video files. 

(3) A .doc file ('Supporting Information') that provides descriptions for the 29 supplementary data files.

(4) Data reproducibility zip, which contains all raw data, code and results. Steps to perform analysis are provided in the R script file ‘RhesusPipeline.R’. Analysis is performed in three stages: first the assembling of count data, second the running of Bayesian models, and finally the collation of posterior distributions of variance and further results. The Datareproducibility zip file contains three directories: scripts are found in ‘Code’, pipeline data in ‘Use_Data’, models are stored in RData. Analysis can be run using relative working directory paths out of the ‘Code’ directory using the respective R, Python and bash scripts. We have also provided our model results in full as stored R data files, with further code templates for parallelised Bayesian model fitting for each bivariate model and additional script templates for stitching chains together after fitting (see script notes in RhesusPipeline.R for details). 
