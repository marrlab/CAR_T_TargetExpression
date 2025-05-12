# Single cell profiling of chimeric antigen receptor (CAR) targets

This repository contains all jupyter notebooks to reproduce the results of the single-cell data analysis from: 

M. Thomas, R. Brabenec et al., "The role of single cell transcriptomics for efficacy and toxicity profiling of chimeric antigen receptor (CAR) T cell therapies", Computers in Biology and Medicine (2025).

The notebooks contain code for the following analyses:

- Clinical efficacy and safety from clinical patient outcome data (Fig. 1)
- CAR target expression across tumor tissues (Fig. 2 and Suppl. Fig. 1)
- CAR target expression across healthy tissues (Fig. 3)
- Correlation of CAR target expression profiles with observed clinical toxicity effects (Suppl. Fig. 2)

Note that the analysis was done in python 3 using ```scanpy``` v.1.4.6 to 1.6.1 and ```anndata``` v.0.7.1 to 0.7.5 unless otherwise stated. Some functions may have changed when using other package versions. 
Additionally, ```numpy``` (v. 1.18.2+), ```pandas``` (v. 1.3.5+) and ```scipy``` (v. 1.4.1+) are required. Numeric results can vary depending on package versions and e.g. minor results. All figures were plotted using ```matplotlib``` and ```seaborn```. 


If the materials in this repository are of use to you, please consider citing the above publication.
