# Fmadrid <img src='static/images/logo.png' align="right" height="139" />

[![Linkedin](https://img.shields.io/static/v1?label=Linkedin&message=Profile&color=darkblue)](https://www.linkedin.com/in/francisco-m-74489010a/)
[![Netlify](https://img.shields.io/static/v1?label=Netlify&message=Page&color=yellow)](https://franciscomadrid.netlify.app/)
[![ORDIC](https://img.shields.io/static/v1?label=ORCID&message=ID&color=lightgreen)](https://orcid.org/0000-0001-9333-0014)
[![Publications](https://img.shields.io/static/v1?label=Scholar&message=Publications&color=blue)](https://scholar.google.es/citations?user=O6jL4bcAAAAJ&hl=es)

Hello world!

I am a researcher 
I hold a Ph.D. in Health Science for biomarkers discovery using untargeted metabolomics techniques, developing different types of work, data mining, lab SOPs, and human intervention studies at the University of Barcelona (2017, Spain). I also made a postdoctoral stay at the Royal College of Surgeons in Ireland (Dublin, Ireland) for a year, investigating the risk of psychosis utilizing omics integration in R studio, in the department of psychiatry at Beaumont Hospital (Dublin, Ireland), and in the nutritional biomarker field in the UCD. This allowed me to take several high-impact factor publications. After coming back to Spain, I worked for more than 2 years at the [Institute for BioEngineering of Catalonia](https://ibecbarcelona.eu/) for a computational project with [Nestlé Institute Health Science](https://www.nestlehealthscience.com/), developing signal processing and machine learning solutions (R packages in [GitHub](https://github.com/sipss) and [Bioconductor](https://www.bioconductor.org/packages/release/bioc/html/AlpsNMR.html)) for metabolomics and proteomics studies.

My current work is involved in the application of biostatistics and machine learning techniques on multiomics in the clinical world for the discovery of biomarkers of exposure, disease, phenotyping, and epidemiology. Assistant professor of statistical learning/biostats at the UPF, UB and IL3.


## About AplsNMR package

`AlpsNMR` can be installed with the `devtools` package. For this is needed
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

Checkout the [fmadrid](https://sipss.github.io/AlpsNMR/articles/introduction-to-alpsnmr.html) vignette that shows how to import data and preprocess it using AlpsNMR. See our [publication](https://doi.org/10.1093/bioinformatics/btaa022) for further details.

