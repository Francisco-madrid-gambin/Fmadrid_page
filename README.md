# Fmadrid <img src='static/images/logo.png' align="right" height="139" />

[![Linkedin](https://img.shields.io/static/v1?label=Linkedin&message=Linkedin&color=darkblue)](https://www.linkedin.com/in/francisco-m-74489010a/)
[![Netlify](https://img.shields.io/static/v1?label=Netlify&message=Netlify&color=darkblue)](https://franciscomadrid.netlify.app/)
[![Bioc Status](https://bioconductor.org/shields/build/devel/bioc/AlpsNMR.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/AlpsNMR/)
[![Documentation](https://img.shields.io/badge/documentation-pkgdown-informational)](https://sipss.github.io/AlpsNMR/)
[![Publications](https://img.shields.io/static/v1?label=Scholar&message=Publications&color=<COLOR>)](https://scholar.google.es/citations?user=O6jL4bcAAAAJ&hl=es)

Hello world.

I hold a Ph.D. in Health Science for biomarkers discovery using untargeted metabolomics techniques, developing different types of work, data mining, lab SOPs, and human intervention studies at the University of Barcelona (2017, Spain). I also made a postdoctoral stay at the Royal College of Surgeons in Ireland (Dublin, Ireland) for a year, investigating the risk of psychosis utilizing omics integration in R studio, in the department of psychiatry at Beaumont Hospital (Dublin, Ireland), and in the nutritional biomarker field in the UCD. This allowed me to take several high-impact factor publications. After coming back to Spain, I worked for more than 2 years at the [Institute for BioEngineering of Catalonia](https://ibecbarcelona.eu/) for a computational project with [Nestlé Institute Health Science](https://www.nestlehealthscience.com/), developing signal processing and machine learning solutions (R packages in [GitHub](https://github.com/sipss) and [Bioconductor](https://www.bioconductor.org/packages/release/bioc/html/AlpsNMR.html)) for metabolomics and proteomics studies.

My current work is involved in the application of biostatistics and machine learning techniques on multiomics in the clinical world for the discovery of biomarkers of exposure, disease, phenotyping, and epidemiology. Assistant professor of statistical learning/biostats at the UPF, UB and IL3.


## Alternative installation

AlpsNMR can be installed with the `devtools` package. For this is needed
Rtools and note that it uses packages from
CRAN, from BioConductor and from git repositories:

If you already have Rtools, follow this to install AlspNMR:

```r
if (!"BiocManager" %in% rownames(installed.packages()))  
    install.packages("BiocManager")  
BiocManager::install(c("MassSpecWavelet", "impute"), update = FALSE)  
if (!"devtools" %in% rownames(installed.packages()))  
    install.packages("devtools")  
devtools::install_github("sipss/AlpsNMR")
```

Quick start
=============

Checkout the [Introduction to AlpsNMR](https://sipss.github.io/AlpsNMR/articles/introduction-to-alpsnmr.html) vignette that shows how to import data and preprocess it using AlpsNMR. See our [publication](https://doi.org/10.1093/bioinformatics/btaa022) for further details.

See also the [tutorial](https://github.com/sipss/AlpsNMR/blob/master/vignettes/tutorial.pdf) with a real dataset from beginning to end, including all the steps of untargeted metabolomics analysis. To run the [tutorial](https://github.com/sipss/AlpsNMR/blob/master/vignettes/tutorial.pdf), you can download the MTBLS242 dataset from the public [MetaboLights repository](https://www.ebi.ac.uk/metabolights/MTBLS242), or download and unzip the contents (spectra and metadata) of this [Dropbox link](https://dl.dropboxusercontent.com/s/0snivrsd7m82yey/MTBLS242.zip?dl=0).
