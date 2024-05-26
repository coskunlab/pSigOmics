# pSigOmics
NFkB pSigOmics

This repository contains code for the manuscript "High Throughput, Programmable Fixation Reveals the RNA and protein co-regulation with Spatially Resolved NFκB Pseudo-signaling". Codes are run under the specified Anaconda environment.

To set up environments, run the following command: `conda env create -f environ.yml`

Example data can be found at: https://zenodo.org/records/11292144

01_dim_reduce_2D_embedding_drug_vs_control.ipynb creates the plot for single cell latent space embeddings (Fig. 4b)

<img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/TNFa_time.png" height="250"> <img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/TNFa_stim.png" height="250"> <img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/TNFa_P-R.png" height="250">

02_boxplot_p65_stim_continuous_drug_vs_control.ipynb plots the NFkB response across static fixation times. It also plots the RNA and protein curves over this time axis to illustrate the anticorrelation effect.

<img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/IL1B_CellCounts_norm.png" height="250"> <img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/TNFa_MedianNucCytoRatio_IQR.png" height="250">
<img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/IL1B_WholeCell.png" height="250"> <img src="https://github.com/coskunlab/pSigOmics/blob/main/figures/TNFa_Cytosol.png" height="250">

# Citation

Please cite: TBD
