# Transplantation_study
This repository includes the codes utilized to analyze the data from the Transplantation study, which has been submitted as paper for peer review. The paper is titled “Full-scale activated sludge transplantation reveals a highly resilient community structure”, authored by Giulia Dottorini, Dorottya Sarolta Wágner, Mikkel Stokholm-Bjerregaard, Sergey Kucheryavskiy, Thomas Yssing Michaelsen, Marta Nierychlo, Miriam Peces, Rohan B. H. Williams, Per Henrik Nielsen, Kasper Skytte Andersen, Per Halkjær Nielsen.

The study investigates the development over time of the microbial community in a recipient full-scale WWTPs after its activated sludge was replaced by 75% of the biomass with the activated sludge from a donor full-scale WWTPs in Denmark. The process parameters, as well as activated sludge and influent wastewater samples were collected regularly before and after transplantation. The microbial community was analyzed by 16S rRNA gene amplicon sequencing. Statistical analyses were applied to identify significant trends over time in the microbial community. The role of mass-immigration was also evaluated.

This repository includes the following scripts that allow to reproduce the results of the study:

 • “1-Load data.Rmd”: it loads the raw amplicon data (ASV table with MiDAS taxonomy), and samples metadata and performs preliminary filtering of dataset. It requires “Additional file 2” and “Additional file 3” provided with the paper submission. It generates files to be used in the following Rmd file.

•	“2-Statistical analysis.Rmd”: it is developed by Prof. Sergey Kucheryavskiy and it performs the main statistical analysis of the study. It requires the “Additional file 4” provided with the paper submission. It generates Figure 2B, Figure S3, Figure S4 and Figure 7. It generates files to be used in the following Rmd file.

•	“3-Analysis and plots.Rmd”: it includes analysis and all main plots included in the paper (from Figure 1 to Figure 8, and Table S3). Codes generated in collaboration with Dorottya Sarolta Wágner and Mikkel Stokholm-Bjerregaard.

•	“4-SI analysis and plots.Rmd”: it includes supplementary analysis and plots found in "Additional file 1" of the paper (Figure S2, Figure S5, Figure S6, and from Figure S8 to Figure S11). Codes generated in collaboration with Dorottya Sarolta Wágner and Mikkel Stokholm-Bjerregaard.

The raw amplicon sequences will be publicly available at NCBI Sequence Reads Archive as project number PRJNA815941.
