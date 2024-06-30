# Evaluate-DNA-methylation
Evaluate DNA methylation-based on Infinium technology of Illumina array chip



**Project Description:**
This project is an extensive study of DNA and RNA dynamics focusing on methylation patterns and their impacts on gene expression. Using R, we delve into various statistical methods to explore and analyze fluorescent intensity data, methylation statuses, and probe characteristics.

**Main Objective:**
The primary aim of this project is to utilize robust statistical tools to evaluate the dynamic behavior of DNA and RNA. This involves assessing probe intensities, methylation levels, and comparing wild type (WT) and mutated (MUT) sequences under different conditions.

**Key Tasks and Methodologies:**
1. **Data Collection and Normalization:** Gather probe data from specified databases, ensuring proper resolution and size criteria. Normalize the data using the 'Noob' preprocessing method for accurate comparisons.
2. **Statistical Analysis:**
   - Perform t-tests to identify significant differences in probe behavior.
   - Analyze fluorescent intensity across different probes, focusing on methylation and unmethylated states.
3. **Visualization:**
   - Generate mean, standard deviation, and box plots to visualize data distributions in normalized and unnormalized states.
   - Produce PCA plots to illustrate clustering based on target traits and groups.
   - Create Volcano and Manhattan plots to depict significant genomic variations.
4. **P-Value Adjustments:** Apply multiple testing corrections, such as Benferroni and BH corrections, to assess the significance of observed differences.

**Technologies Used:**
- R programming language for all data analysis and visualization tasks.
- PDBeFold and other bioinformatics tools for sequence alignment and structural comparisons.

**Outcome:**
This project aims to provide insights into how methylation influences gene expression and probe behavior, offering valuable data for further research in genomics and epigenetics.

**Repository Contents:**
- R scripts for data analysis and plotting.
- Documentation detailing the project's scope, methodology, and findings.
