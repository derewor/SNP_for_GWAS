
# Project Title

Identification of SNPs associated with root growth inhibition trait induced by Isoleucic Acid (ILA)


## Table of Content

    Project Description

    Tools

    Usage

    Project Structure

    Results

    Contact
## Project Description
ILA has recently been identified as a key biomolecule involved in coordinating plant defense responses against pathogen attack. In addition, our group demonstrated that ILA also plays an important role in the physiological growth of Arabidopsis. Besides inhibiting root growth in in vitro assays at micromolar concentrations, mutants with altered endogenous ILA levels, generated through knockout and overexpression of its catabolizing enzyme UGT76B1, also showed altered shoot growth phenotypes.

As a recently discovered molecule, little is known about the metabolic pathway of ILA and the genes involved in its regulatory network. This project aimed to identify potential target genes through the detection of associated SNP markers. To achieve this, we performed root growth assays on more than 400 Arabidopsis accessions and selected approximately 250 lines with reliable germination and growth performance for further analysis. SNP data were extracted from the Arabidopsis 1001 Genomes database, filtered based on minor allele frequency (MAF), linkage disequilibrium (LD)-pruned, and subsequently used for genome-wide association studies (GWAS) using TASSEL.
## Tools
Google colab, Python/Pandas, Excel sheet, Google drive, TASSEL, STRUCTURE, Data Visualization tools (seaborn)
## USAGE
To reproduce the result, the code can be run in google colab or jypyter notebook provided that the data are available. The two files in src directory of the GitHub project contain codes for importing and cleaning of the SNPs from the 1001 genome and the second for downstream analysis.
## Project Structure
Data/: A folder that contains the phenotype data used for the analysis. 

src/: A googlecolab notebook with an active code.

Results/: Contains the results of the Manhattan Plot and QQ plot for the SNPs with p-values lower than 10-3. 

README.md/: file that outlines the project

## Results
Several SNPs with p-values lower than 10⁻⁶ were identified during the association analysis. However, false discovery rate (FDR) correction of the p-values using the Python statsmodels package revealed that none of the SNPs remained significantly associated.
## Author
email: derewor@gmail.com

LinkedIn: https://www.linkedin.com/in/dereje-worku-mekonnen-a8345217/?skipRedirect=true$0
