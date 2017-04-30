The QUAERO French Medical Corpus is released under the GNU Free Documentation License (GFDL) http://en.wikipedia.org/wiki/Wikipedia:Text_of_the_GNU_Free_Documentation_License. 

Any research using this corpus for running experiments should include at least one of the following citations, as appropriate: 

Névéol A, Grouin C, Leixa J, Rosset S, Zweigenbaum P. The QUAERO French Medical Corpus: A Ressource for Medical Entity Recognition and Normalization. Fourth Workshop on Building and Evaluating Ressources for Health and Biomedical Text Processing - BioTxtM2014. 2014:24-30

Névéol A, Grouin C, Tannier X, Hamon T, Kelly L, Goeuriot L, Zweigenbaum P. (2015) Task 1b of the CLEF eHealth Evaluation Lab 2015: Clinical Named Entity Recognition. CLEF 2015 Evaluation Labs and Workshop: Online Working Notes, CEUR-WS, September, 2015.

Névéol A, Grouin C, Cohen KB, Hamon T, Lavergne T, Kelly L, Goeuriot L, Rey G, Robert A, Tannier X,  Zweigenbaum P. (2016) Clinical information extraction at the CLEF eHealth Evaluation lab 2016. CLEF 2016 Evaluation Labs and Workshop: Online Working Notes, CEUR-WS, September, 2016.

This work has been partially funded by OSEO under the Quaero program and by the French ANR Cabernet project (ANR-13-JS02-0009).

========================
The QUAERO French Medical Corpus, BioC release
========================

The QUAERO French Medical Corpus BioC release comprises a subset of the QUAERO French Medical corpus, as follows:

Training data (BRAT version used in CLEF eHealth 2015 task 1b as training data): 
- MEDLINE_train_bioc file: 833 MEDLINE titles, annotated with normalized entities in the BioC format 
- EMEA_train_bioc file: 3 EMEA documents, segmented into 11 sub-documents, annotated with normalized entities in the BioC format 

Development data  (BRAT version used in CLEF eHealth 2015 task 1b as test data and in CLEF eHealth 2016 task 2 as development data): 
- MEDLINE_dev_bioc file: 832 MEDLINE titles, annotated with normalized entities in the BioC format
- EMEA_dev_bioc file: 3 EMEA documents, segmented into 12 sub-documents, annotated with normalized entities in the BioC format 

Test data (BRAT version used in CLEF eHealth 2016 task 2 as test data): 
- MEDLINE_test_bioc folder: 833 MEDLINE titles, annotated with normalized entities in the BioC format 
- EMEA folder_test_bioc: 4 EMEA documents, segmented into 15 sub-documents, annotated with normalized entities in the BioC format 



This release of the QUAERO French medical corpus, BioC version, comes in the BioC format, through automatic conversion from the original BRAT format obtained with the Brat2BioC tool https://bitbucket.org/nicta_biomed/brat2bioc developped by Jimeno Yepes et al.

Antonio Jimeno Yepes, Mariana Neves, Karin Verspoor 
Brat2BioC: conversion tool between brat and BioC
BioCreative IV track 1 - BioC: The BioCreative Interoperability Initiative, 2013


Please note that the original version of the QUAERO corpus distributed in the CLEF eHealth challenge 2015 and 2016 came in the BRAT stand alone format. It was distributed with the CLEF eHealth evaluation tool. This original distribution of the QUAERO French Medical corpus is available separately from https://quaerofrenchmed.limsi.fr  

All questions regarding the task or data should be addressed to aurelie.neveol@limsi.fr

