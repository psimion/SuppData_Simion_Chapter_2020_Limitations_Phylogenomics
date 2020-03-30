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


## Section: Cleaning outlier sequences and genes in turtle phylogenomics

**Turtles_supermatrices**  
Contains supermatrices corresponding to the combinations of data (AA, NT123, NT12), filtering methods (none, BT, BLC, TS) and format (nexus, phylip) presented in Figure 4.

**Turtles_trees**  
Contains all trees corresponding to the analyses of the supermatrices (see above) under either a fixed (GTR+G or LG+G) or a partitionned evolution model per gene (modelFinder) as presented in Figure 4.


## Section: Random contamination and short internal branches

**RandomContamination_Supp_Table_1.docx**  
Details the scheme followed for creating chimeras during gene concatenation in order to reduce missing data

**RandomContamination_143_gene_alignments.tgz**  
Contains the 143 gene alignments that were retained for the simulation of random contamination


## Section: Reappraisal of phylogenomic signal dissection methods

**CTA_unconstrained.gene-wise**  
Contains 5 AU tests files comparing unconstrained gene trees to several contrained topologies using 5 evolution models on the 89 genes composing the "D16_Opisthokonta" dataset from Whelan et al. 2015 and re-analyzed by Shen et al. 2017)

**CTA_constrained.gene-wise**  
These 5 AU tests comparing contrained topologies against each other using 5 evolution models on the 89 genes composing the "D16_Opisthokonta" dataset from Whelan et al. 2015 and re-analyzed by Shen et al. 2017)

**CTA_site-wise.ll.allsites.tvs**  
This file contains all per-site likelihoods for the 23,676 sites corresponding to the 89 genes analyzed, for both unconstrained and contrained trees, across 5 evolution models. Columns name are self-explanatory, and every line corresponds to a given site.


## Section: Opening the phylogenomic black box

Pending upload...  
Due to confinement policies, we are temporarily unable to access the supportive data for this section.
We apologize to the readers, this will be fixed as soon as we can !






