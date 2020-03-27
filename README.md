SuppData_Simion_Chapter_2020_Limitations_Phylogenomics
---

This repository contains supplemental materials from :

Paul Simion, Frédéric Delsuc, and Hervé Philippe (2020). **To What Extent Current
Limits of Phylogenomics Can Be Overcome?**. In Céline Scornavacca, Frédéric Delsuc and Nicolas
Galtier editors, PGE; Chapter No. 2.1; pp. 2.1:1–2.1:33. No commercial publisher | Authors open
access book.


## Section: Correcting data errors in tunicates

**DataCorrection_Standard.genes.tgz**  
Contains the 408 genes obtained through the "Standard" pipeline

**DataCorrection_Standard.supermatrix**  
Contains the 4 "Standard" supermatrices build from the 408 genes, with various filtering of missing data (i.e. removal of columns if its amount of missing data was more or equal to 100%, 80%, 50% or 20%)

**DataCorrection_Corrected.genes.tgz**  
Contains the 3,039 genes obtained through the "Corrected" pipeline

**DataCorrection_Corrected.supermatrix**  
Contains the 4 "Corrected" supermatrices build from the 3,039 genes, with various filtering of missing data (i.e. removal of columns if its amount of missing data was more or equal to 100%, 80%, 50% or 20%)


## Section: Random contamination and short internal branches

**RandomContamination_Supp_Table_1.docx**  
Details the scheme followed for creating chimeras during gene concatenation in order to reduce missing data

**RandomContamination_143_gene_alignments.tgz**  
Contains the 143 gene alignments that were retained for the simulation of random contamination



## Section: Reappraisal of phylogenomic signal dissection methods

**CTA_unconstrained.gene-wise.C60+R4+F.AU_tests**  
**CTA_unconstrained.gene-wise.EX_EHO+R4+F.AU_tests**  
**CTA_unconstrained.gene-wise.GTR20+F+R4.AU_tests**  
**CTA_unconstrained.gene-wise.LG+R4+F.AU_tests**  
**CTA_unconstrained.gene-wise.Poisson+R4+F.AU_tests**  
These 5 files contain the AU tests comparing unconstrained gene trees to several contrained topologies using 5 evolution models on the 89 genes composing the "D16_Opisthokonta" dataset from Whelan et al. 2015 and re-analyzed by Shen et al. 2017)

**CTA_gene-wise.C60+R4+F.AU_tests**  
**CTA_gene-wise.EX_EHO+R4+F.AU_tests**  
**CTA_gene-wise.GTR20+F+R4.AU_tests**  
**CTA_gene-wise.LG+R4+F.AU_tests**  
**CTA_gene-wise.Poisson+R4+F.AU_tests**  
These 5 files contain the AU tests comparing contrained topologies against each other using 5 evolution models on the 89 genes composing the "D16_Opisthokonta" dataset from Whelan et al. 2015 and re-analyzed by Shen et al. 2017)

**CTA_site-wise.ll.allsites.tvs**  
This file contains all per-site likelihoods for the 23,676 sites corresponding to the 89 genes analyzed, for both unconstrained and contrained trees, across 5 evolution models. Columns name are self-explanatory, and every line corresponds to a given site.











