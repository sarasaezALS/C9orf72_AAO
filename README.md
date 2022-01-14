# Genetic modifiers of age at onset in ALS/FTD patients carrying *C9orf72* repeat expasions

--------------




## Introduction

A notable feature of *C9orf72*-related neurodegeneration is the wide range of onset observed among patients. Despite the efforts made since its discovery, little is known about the genetic modifiers of C9orf72 age at onset. This work investigates age at onset genetic modifiers of *C9orf72*-related neurodegeneration and nominate drugs that may delay age at onset in these patients.

--------

## Overview

Polygenic risk score analyses were used to identify genetic modifiers of *C9orf72*, using the following datasets:

**Reference Dataset.** A published GWAS study involving 12,577 ALS cases and 23,475 controls (*Van Rheenen et al., 2016*)
https://www.ncbi.nlm.nih.gov/pubmed/27455348


**Training Dataset**. 	Plink Binary files containing individual-level data consisting in 7,037 ALS cases not carrying *C9orf72* repeat expansions and 34,236 control subjects that were genotyped in our laboratory *(Nicolas et al., 2018)*.
https://www.ncbi.nlm.nih.gov/pubmed/29566793

**Test Dataset.** Plink Binary files containing individual-level data consisting in  817 ALS/FTD cases known to carry *C9orf72* repeat expansions *(Nicolas et al., 2018 & Dewan et al., 2021)*. https://www.ncbi.nlm.nih.gov/pubmed/29566793 & https://pubmed.ncbi.nlm.nih.gov/33242422/


**Replication Dataset.** Plink Binary files containing individual-level data consisting in  699 ALS/FTD cases known to carry *C9orf72* repeat expansions *(Unpublished data provided by Isabella Fogh at King's College London, London, UK)*. 

-----------------------

## Available codes

Code for each analysis are deposited as individual notebooks in the following folders. 

01.   `Genetic risk score analysis`


02. `Leave-one-out analysis & pathway analysis`


03. `Individual variant age at onset regression`


04. `Genome for repositioning analysis (GREP)`


05. `Transcriptomic analysis & Conectivity score (Cmap)`


