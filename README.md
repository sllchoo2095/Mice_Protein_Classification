# Mice_Protein_Classification
Classification of the Mice Protein Expression Data set from the UCI Machine Learning Repository https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression. Aimed to classify control vs. down syndrome mice (with different treatments and behaviours) by their protein expression levels. The mice are in 8 classes which are defined by their genotype (c=control/t=trisomy), behaviour (CS=stimulated to learn/ SC= not stimulated to learn) and injection treatment (s=saline/ m=memantine).

## Summary of Analysis: 
SOD1_N, pPKCG_N and APP_N were identified by both random forest and decision tree models to be among the most important proteins to consider to classify mice. 
However, rankings of other proteins vary depending on decision tree and random forest algorithm. Further steps to produce classifiers for genotype, behaviour and 
treatment indivudually, as opposed to combined classes. Some proteins may not be important for classifying a combination of all three categories, but only one of them. 

## Changelog: 
#### 14th August 2020: This is an ongoing project, with analysis yet to be finalised. 
