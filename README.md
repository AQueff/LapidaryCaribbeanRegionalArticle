# LapidaryCaribbeanRegionalArticle
This is the repository for the data and code of an article written in Quarto, with R code inside, about the spatio-temporal diversity and distribution of lithic beads and pendants during the Ceramic Age in the Caribbean islands.

This article is based on one of my PhD dissertation chapter, available in French (but with English papers inside): https://theses.hal.science/tel-03994566

The preprint as a pdf is available [here](https://osf.io/preprints/socarxiv/r9vmp/) with tables generated via direct LaTeX code in the .qmd document.

## This repository contains
- Quarto document for html rendering with R chuncks for Diversity analysis (Diversity profiles, modelling of diversity) and Similarity analysis (heatmaps and seriations, networks, correspondence analysis)
- Quarto document for pdf rendering with same content except tables are made directly in LaTeX. Unfortunately I did not manage to cross-reference the LaTeX tables in quarto document.
- Data as .csv files
- Tables as .csv files
- JPG and PNG files for some figures which are not created via the code
- Bibtek file for the bibliography cited in the manuscript

## Advice
- for tries, consider setting the number simulations to 100 instead of 10000 in all 5 plots including modelling of the potential diversity (just search for the "nsim=10000" value to find them)
