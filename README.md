# Transplantation_study
This repository includes the codes utilized to analyze the data from the Transplantation study, which has been submitted as paper for peer review. The paper is titled “Full-scale activated sludge transplantation reveals a highly resilient community structure”, authored by Giulia Dottorini, Dorottya Sarolta Wágner, Mikkel Stokholm-Bjerregaard, Sergey Kucheryavskiy, Thomas Yssing Michaelsen, Marta Nierychlo, Miriam Peces, Rohan B. H. Williams, Per Henrik Nielsen, Kasper Skytte Andersen, Per Halkjær Nielsen.

This repository includes the following scripts that allow to reproduce the results of the study:

 • “1-Load data.Rmd”: it loads the raw amplicon data (ASV table with MiDAS taxonomy), and samples metadata and performs preliminary filtering of dataset. It requires “Supplementary data 2” and “Supplementary data 3” provided with the paper submission. It generates files to be used in the following Rmd file.

•	“2A-Data preprocessing.Rmd”: it is developed by Prof. Sergey Kucheryavskiy and it performs the data preprocessing needed for statistical analysis. It generates files to be used in the following Rmd file.

•	“2B-Statistical analysis.Rmd”: it is developed by Prof. Sergey Kucheryavskiy and it performs the main statistical analysis of the study. It generates Figure 2B, Figure S3, Figure S4 and Figure 7. It generates files to be used in the following Rmd file.

•	“3-Analysis and plots.Rmd”: it includes analysis and all main plots included in the paper (from Figure 1 to Figure 8, and Table S3). Codes generated in collaboration with Dorottya Sarolta Wágner and Mikkel Stokholm-Bjerregaard.

•	“4-SI analysis and plots.Rmd”: it includes supplementary analysis and plots found in "Supplementary files" of the paper (Figure S2, Figure S5, Figure S6, and from Figure S8 to Figure S11). Codes generated in collaboration with Dorottya Sarolta Wágner and Mikkel Stokholm-Bjerregaard.

The raw amplicon sequences will be publicly available at NCBI Sequence Reads Archive as project number PRJNA815941.
