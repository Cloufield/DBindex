# PRS methods and tools:
- PLINK2
- PRSice-2
- PRSet
- LDpred2
- PRS-CS
- lassosum
- PRS-CSx
- Multi-PGS
- PGSCatalog
- wMT-SBLUP
- pgsc_calc
- VIPRS
- MegaPRS
- SBayesS
- ExPRSweb
- Cancer PRSweb
- PRS atlas
- metabolites PRS atlas

## PRS Tutorial
- SHORT NAME: PRS Tutorial
- FULL NAME: PRS Tutorial
- DESCRIPTION: This tutorial provides a step-by-step guide to performing basic polygenic risk score (PRS) analyses and accompanies our PRS Guide paper. The aim of this tutorial is to provide a simple introduction of PRS analyses to those new to PRS, while equipping existing users with a better understanding of the processes and implementation "underneath the hood" of popular PRS software.
- URL : https://choishingwan.github.io/PRS-Tutorial/
- CITATION: Choi, S. W., Mak, T. S. H., & O’Reilly, P. F. (2020). Tutorial: a guide to performing polygenic risk score analyses. Nature protocols, 15(9), 2759-2772.

## PLINK2
- SHORT NAME: PLINK2 
- FULL NAME: PLINK2
- DESCRIPTION: The second-generation versions of PLINK will offer dramatic improvements in performance and compatibility.
- URL :  https://www.cog-genomics.org/plink/2.0/
- CITATION: Chang, C.C., Chow, C.C., Tellier, L.C. et al. Second-generation PLINK: rising to the challenge of larger and richer datasets. GigaSci 4, 7 (2015). https://doi.org/10.1186/s13742-015-0047-8
- USE: calculate PRS using genotype data.

## PRSice-2
- SHORT NAME: PRSice-2
- FULL NAME: PRSice-2
- DESCRIPTION: PRSice (pronounced 'precise') is a Polygenic Risk Score software for calculating, applying, evaluating and plotting the results of polygenic risk scores (PRS) analyses.
- URL : https://www.prsice.info/
- CITATION: Shing Wan Choi, Paul F O'Reilly, PRSice-2: Polygenic Risk Score software for biobank-scale data, GigaScience, Volume 8, Issue 7, July 2019, giz082, https://doi.org/10.1093/gigascience/giz082

## PRSet
- SHORT NAME: PRSet
- FULL NAME: PRSet
- DESCRIPTION: A new feature of PRSice is the ability to perform set base/pathway based analysis. This new feature is called PRSet.
- URL : https://www.prsice.info/quick_start_prset/
- CITATION: Choi SW, Garcia-Gonzalez J, Ruan Y, et al. The power of pathway-based polygenic risk scores. Research Square; 2021. DOI: 10.21203/rs.3.rs-643696/v1.
- KEY WORDS: pathway-based

## LDpred2
- SHORT NAME: LDpred2
- FULL NAME: LDpred2
- DESCRIPTION: LDpred-2 is one of the dedicated PRS programs which is an R package that uses a Bayesian approach to polygenic risk scoring.
- URL : https://privefl.github.io/bigsnpr/articles/LDpred2.html
- CITATION: Privé, F., Arbel, J., & Vilhjálmsson, B. J. (2020). LDpred2: better, faster, stronger. Bioinformatics, 36(22-23), 5424-5431.
- KEY WORDS: Bayesian

## PRS-CS
- SHORT NAME: PRS-CS
- FULL NAME: PRS-CS
- YEAR: 2019
- DESCRIPTION: PRS-CS is a Python based command line tool that infers posterior SNP effect sizes under continuous shrinkage (CS) priors using GWAS summary statistics and an external LD reference panel.
- URL : https://github.com/getian107/PRScs
- CITATION: Ge, T., Chen, CY., Ni, Y. et al. Polygenic prediction via Bayesian regression and continuous shrinkage priors. Nat Commun 10, 1776 (2019). https://doi.org/10.1038/s41467-019-09718-5
- KEY WORDS: continuous shrinkage (CS) prior

## lassosum
- SHORT NAME: lassosum
- FULL NAME: lassosum
- YEAR: 2017
- DESCRIPTION: lassosum is a method for computing LASSO/Elastic Net estimates of a linear regression problem given summary statistics from GWAS and Genome-wide meta-analyses, accounting for Linkage Disequilibrium (LD), via a reference panel.
- URL : https://github.com/tshmak/lassosum
- CITATION: Mak, T. S. H., Porsch, R. M., Choi, S. W., Zhou, X., & Sham, P. C. (2017). Polygenic scores via penalized regression on summary statistics. Genetic epidemiology, 41(6), 469-480.
- KEY WORDS: penalized regression

## PRS-CSx
- SHORT NAME: PRS-CSx
- FULL NAME: PRS-CSx
- YEAR: 2022
- DESCRIPTION: PRS-CSx is a Python based command line tool that integrates GWAS summary statistics and external LD reference panels from multiple populations to improve cross-population polygenic prediction. Posterior SNP effect sizes are inferred under coupled continuous shrinkage (CS) priors across populations. 
- URL : https://github.com/getian107/PRScsx
- CITATION: Ruan, Y., Lin, YF., Feng, YC.A. et al. Improving polygenic prediction in ancestrally diverse populations. Nat Genet 54, 573–580 (2022). https://doi.org/10.1038/s41588-022-01054-7
- KEY WORDS: continuous shrinkage (CS) prior,  cross-population

## Multi-PGS
- SHORT NAME: Multi-PGS
- YEAR: 2022
- FULL NAME: Multi-PGS
- DESCRIPTION: a framework to generate enriched PGS from a wealth of publicly available genome-wide association studies, combining thousands of studies focused on many different phenotypes, into a multi-PGS
- URL : https://github.com/ClaraAlbi/paper_multiPGS
- CITATION: https://www.medrxiv.org/content/10.1101/2022.09.14.22279940v1

## wMT-SBLUP
- SHORT NAME: wMT-SBLUP
- YEAR: 2018
- FULL NAME: weighted approximate multi-trait summary statistic BLUP
- URL : https://github.com/uqrmaie1/smtpred
- CITATION: Maier, R.M., Zhu, Z., Lee, S.H. et al. Improving genetic prediction by leveraging genetic correlations among human diseases and traits. Nat Commun 9, 989 (2018). https://doi.org/10.1038/s41467-017-02769-6

## PGSCatalog
- SHORT NAME: PGS Catalog
- FULL NAME: PGS Catalog
- DESCRIPTION: The PGS Catalog is an open database of published polygenic scores (PGS). Each PGS in the Catalog is consistently annotated with relevant metadata; including scoring files (variants, effect alleles/weights), annotations of how the PGS was developed and applied, and evaluations of their predictive performance.
- URL : https://www.pgscatalog.org/
- CITATION: Lambert, S. A., Gil, L., Jupp, S., Ritchie, S. C., Xu, Y., Buniello, A., ... & Inouye, M. (2021). The Polygenic Score Catalog as an open database for reproducibility and systematic evaluation. Nature Genetics, 53(4), 420-425.
- KEY WORDS: PGS database

## pgsc_calc
- SHORT NAME: pgsc_calc
- FULL NAME: The Polygenic Score Catalog Calculator
- YEAR: 2022
- DESCRIPTION: pgsc_calc is a bioinformatics best-practice analysis pipeline for calculating polygenic [risk] scores on samples with imputed genotypes using existing scoring files from the Polygenic Score (PGS) Catalog and/or user-defined PGS/PRS.
- URL : https://github.com/PGScatalog/pgsc_calc
- CITATION: https://github.com/PGScatalog/pgsc_calc
- KEY WORDS: PRS calculation pipeline

## VIPRS
- SHORT NAME: VIPRS
- FULL NAME: Variational inference of polygenic risk scores
- YEAR: 2022
- DESCRIPTION: viprs is a python package that implements scripts and utilities for running variational inference algorithms on genome-wide association study (GWAS) data for the purposes polygenic risk estimation.
- URL : https://github.com/shz9/viprs
- CITATION: Zabad, S., Gravel, S., & Li, Y. (2022). Fast and Accurate Bayesian Polygenic Risk Modeling with Variational Inference. bioRxiv.
- KEY WORDS:  Variational Inference (VI)

## ExPRSweb
- SHORT NAME: ExPRSweb
- FULL NAME: exposure polygenic risk scores (ExPRSs)
- YEAR: 2022
- DESCRIPTION: Integrating published and freely available genome-wide association studies (GWAS) summary statistics from multiple sources (published GWAS, the NHGRI-EBI GWAS Catalog, FinnGen- or UKB-based GWAS), we created an online repository for exposure polygenic risk scores (ExPRS) for health-related exposure traits. Our framework condenses these summary statistics into ExPRS using linkage disequilibrium pruning and p-value thresholding (P&T) or penalized, genome-wide effect size weighting. We evaluate them in the cohort of the Michigan Genomics Initiative (MGI), a longitudinal biorepository effort at Michigan Medicine, and in the population-based UK Biobank Study (UKB). For each ExPRS construct, measures on performance, accuracy, and discrimination are provided. Beyond the ExPRS evaluation in MGI and UKB, the ExPRSweb platform features construct downloads, evaluation in the top percentiles, and phenome-wide ExPRS association studies (ExPRS-PheWAS) for a subset of ExPRS that are predictive for the corresponding exposure.
- URL : https://exprsweb.sph.umich.edu:8443/
- CITATION: Ma, Y., Patil, S., Zhou, X., Mukherjee, B., & Fritsche, L. G. (2022). ExPRSweb-An Online Repository with Polygenic Risk Scores for Common Health-related Exposures. medRxiv.
- KEY WORDS: exposure PRS

## Cancer PRSweb
- SHORT NAME: Cancer PRSweb
- FULL NAME: Cancer PRSweb
- YEAR: 2020
- DESCRIPTION: Our framework condenses these summary statistics into PRS using linkage disequilibrium pruning and p-value thresholding (fixed or data-adaptively optimized thresholds) or penalized, genome-wide effect size weighting. We evaluate them in the cancer-enriched cohort of the Michigan Genomics Initiative (MGI), a longitudinal biorepository effort at Michigan Medicine, and in the population-based UK Biobank Study (UKB). For each PRS construct, measures on performance, calibration, and discrimination are provided. Beyond the cancer PRS evaluation in MGI and UKB, the PRSweb platform features construct downloads, risk evaluation in the top percentiles, and phenome-wide PRS association studies (PRS-PheWAS) for a subset of PRS that are predictive for the primary cancer.
- URL : https://prsweb.sph.umich.edu:8443/
- CITATION: Fritsche, L. G., Patil, S., Beesley, L. J., VandeHaar, P., Salvatore, M., Ma, Y., ... & Mukherjee, B. (2020). Cancer PRSweb: an online repository with polygenic risk scores for major cancer traits and their evaluation in two independent biobanks. The American Journal of Human Genetics, 107(5), 815-836.
- KEY WORDS: Cancer PRS

## PRS atlas  
- SHORT NAME: PRS atlas
- FULL NAME: PRS atlas
- DESCRIPTION: This web application can be used to query findings from an analysis of 162 polygenic risk scores and 551 complex traits using data from the UK Biobank study1. Traits were selected based on the heritability analysis conducted by the Neale Lab2 (P<0.05). We encourage users of this resource to conduct follow-up analyses of associations to robustly identify causal relationships between complex traits.
- URL : http://mrcieu.mrsoftware.org/PRS_atlas/
- CITATION: Richardson, T. G., Harrison, S., Hemani, G., & Smith, G. D. (2019). An atlas of polygenic risk score associations to highlight putative causal relationships across the human phenome. Elife, 8, e43657.

## metabolites PRS atlas
- SHORT NAME: metabolites PRS atlas
- FULL NAME: metabolites PRS atlas
- DESCRIPTION: This web application can be used to query findings from a systematic analysis of 129 polygenic risk scores and 249 circulating metabolits using high-throughput nuclear magnetic resonance data from the UK Biobank study1,2. We encourage users of this resource to conduct follow-up analyses of associations to investigate potential causal and non-causal metabolic biomarkers. Age-stratified results can be used to investigate how potential sources of collider bias (e.g. statin therapy) may influence findings in the full sample
- URL : http://mrcieu.mrsoftware.org/metabolites_PRS_atlas/
- CITATION:Fang, S., Holmes, M. V., Gaunt, T. R., Smith, G. D., & Richardson, T. G. (2022). Constructing an atlas of associations between polygenic scores from across the human phenome and circulating metabolic biomarkers. eLife.

## Reviews&Tutorial
- CITATION: Peter M. Visscher,Loic Yengo,Nancy J. Cox,Naomi R. Wray,Discovery and implications of polygenicity of common diseases, Science, 373, 6562, (1468-1473), (2021). /doi/10.1126/science.abi8206