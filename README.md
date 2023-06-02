# Gene Set Variation Analysis (GSVA)

This repositiry contains code to run a Gene Set Variation Analysis using the 'GSVA' package (Hänzelmann et al., 2013). 

GSVA is derivative of a traditional differential expression technique, and provides enrichment scores of gene sets related to genes outside the set. These enrichment scores can then be used by limma. Please note thatGSVA  uses a random walk approach (Hänzelmann et al., 2013). 

There are **five** analyses in this repository
 #1 Gene Set Variation Analyses
 #2 Volcano Plotting of GSVA Effect Sizes 
 #3 Plotting GSVA Enrichment Scores Stratified by Variables (Dx, Reported Race, Institution)
 #4 Semantic Clustering of top 50 Differentially Enriched Gene Sets (Up- and Down-Regulated)
 #5 Plotting GSVA Controlled Transcriptional Response to Adversity (CTRA) Effect Sizes Across Terms

There are **two** files 
1) Driver Script (.rmd with functions)
2) Script (.rmd calling the functions)
