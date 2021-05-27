GWAS to single cell: Intersecting single-cell transcriptomics and genome wide association studies identifies crucial cell-populations and candidate genes for atherosclerosis.
===========================================================

[![DOI](https://zenodo.org/badge/283594863.svg)](https://zenodo.org/badge/latestdoi/283594863)

### This readme
This readme accompanies the paper _"GWAS to single cell: Intersecting single-cell transcriptomics and genome wide association studies identifies crucial cell-populations and candidate genes for atherosclerosis."_ by [Slenders L. *et al*. **bioRxiv 2021**]().

--------------

### Abstract
<!-- Please add a brief introduction to explain what the project is about    -->

**Background**<br/>
Genome-wide association studies (GWAS) have discovered hundreds of common genetic variants for atherosclerotic disease and cardiovascular risk factors. The translation of susceptibility loci into biological mechanisms and targets for drug discovery remains challenging. Intersecting genetic and gene expression data has led to identification of candidate genes. However, the assayed tissues are often non-diseased and heterogeneous in cell composition confounding the candidate prioritization. We collected single-cell transcriptomics (scRNA-seq) from atherosclerotic plaques and aimed to identify cell-type-specific expression of disease-associated genes. 

**Methods and Results**<br/>
To identify disease-associated candidate genes, we applied gene-based analyses using GWAS summary statistics from 46 atherosclerotic, cardiometabolic, and other traits. Next we intersected these candidates with single-cell transcriptomics (scRNA-seq) to identify those genes that are specifically expressed in individual cell (sub)populations of atherosclerotic plaques. We derive an enrichment score and show that loci that associated with coronary artery disease demonstrated a prominent substrate in plaque smooth muscle cells (_SKI_, _KANK2_, _SORT1_), endothelial cells (_SLC44A1_, _ATP2B1_), and macrophages (_APOE_, _HNRNPUL1_). Further sub clustering of SMC-subtypes revealed genes in risk loci for coronary calcification specifically enriched in a synthetic cluster of SMCs. To verify the robustness of our approach, we used liver-derived scRNAseq-data and showed enrichment of circulating lipids-associated loci in hepatocytes. 

**Conclusion**<br/>
We confirm known gene-cell pairs relevant for atherosclerotic disease, and discovered novel pairs pointing to new biological mechanisms amenable for therapy. We present an intuitive single-cell transcriptomics driven workflow rooted in human large-scale genetic studies to identify putative candidate genes and affected cells associated with cardiovascular traits.

<!-- ![**Figure 1: An intuitive single-cell transcriptomics driven workflow using human genetics to identify cardiovascular candidate genes and relevant cells.** Adapted from [Slenders L. *et al*. **bioRxiv 2021**]()](figures/Figure1.png) -->


--------------

### This project

#### Where do I start?

You can load this project in RStudio by opening the file called 'gwas2single.Rproj'.

#### Project structure

<!--  You can add rows to this table, using "|" to separate columns.         -->
File              | Description                | Usage         
----------------- | -------------------------- | --------------
README.md         | Description of project     | Human editable
gwas2single.Rproj | Project file               | Loads project 
LICENSE           | User permissions           | Read only     
.worcs            | WORCS metadata YAML        | Read only     
prepare_data.R    | Script to process raw data | Human editable
renv.lock         | Reproducible R environment | Read only     

<!--  You can consider adding the following to this file:                    -->
<!--  * A citation reference for your project                                -->
<!--  * Contact information for questions/comments                           -->
<!--  * How people can offer to contribute to the project                    -->
<!--  * A contributor code of conduct, https://www.contributor-covenant.org/ -->

### Reproducibility

This project uses the Workflow for Open Reproducible Code in Science (WORCS) to
ensure transparency and reproducibility. The workflow is designed to meet the
principles of Open Science throughout a research project. 

To learn how WORCS helps researchers meet the TOP-guidelines and FAIR principles,
read the preprint at https://osf.io/zcvbs/

#### WORCS: Advice for authors

* To get started with `worcs`, see the [setup vignette](https://cjvanlissa.github.io/worcs/articles/setup.html)
* For detailed information about the steps of the WORCS workflow, see the [workflow vignette](https://cjvanlissa.github.io/worcs/articles/workflow.html)

#### WORCS: Advice for readers

Please refer to the vignette on [reproducing a WORCS project]() for step by step advice.
<!-- If your project deviates from the steps outlined in the vignette on     -->
<!-- reproducing a WORCS project, please provide your own advice for         -->
<!-- readers here.                                                           -->

### Acknowledgements

Dr. Sander W. van der Laan is funded through grants from the Netherlands CardioVascular Research Initiative of the Netherlands Heart Foundation (CVON 2011/B019 and CVON 2017-20: Generating the best evidence-based pharmaceutical targets for atherosclerosis [GENIUS I&II]). We are thankful for the support of the ERA-CVD program ‘druggable-MI-targets’ (grant number: 01KL1802), the EU H2020 TO_AITION (grant number: 848146), and the Leducq Fondation ‘PlaqOmics’.

Plaque samples are derived from carotid endarterectomies as part of the [Athero-Express Biobank Study](http:www/atheroexpress.nl) which is an ongoing study in the UMC Utrecht.

The framework was based on the [`WORCS` package](https://osf.io/zcvbs/).

<a href='https://www.era-cvd.eu'><img src='images/ERA_CVD_Logo_CMYK.png' align="center" height="75" /></a> <a href='https://www.plaqomics.com'><img src='images/leducq-logo-large.png' align="center" height="75" /></a> <a href='https://www.fondationleducq.org'><img src='images/leducq-logo-small.png' align="center" height="75" /></a> <a href='https://www.to-aition.eu'><img src='images/to_aition_logo.png' align="center" height="75" /></a> <a href='https://osf.io/zcvbs/'><img src='images/worcs_icon.png' align="center" height="75" /></a>

##### Changes log
    
    _Version:_      v1.0.0</br>
    _Last update:_  2021-05-27</br>
    _Written by:_   Sander W. van der Laan (s.w.vanderlaan-2[at]umcutrecht.nl).
    
    * v1.0.0 Initial version. 

--------------

#### Creative Commons BY-NC-ND 4.0
##### Copyright (c) 1979-2021 Sander W. van der Laan | s.w.vanderlaan [at] gmail [dot] com.

This is a human-readable summary of (and not a substitute for) the [license](LICENSE). 

You are free to: 
Share — copy and redistribute the material in any medium or format. The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms: 
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. 
- NonCommercial — You may not use the material for commercial purposes. 
- NoDerivatives — If you remix, transform, or build upon the material, you may not distribute the modified material. 
- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices: 
You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.


