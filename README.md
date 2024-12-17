## Project6-VariantConsequences

Project Overview

This project analyzes genetic variants from the 1000 Genomes Project to:

Identify sickle cell variant carriers (rs334 in the HBB gene).
Detect pathogenic CFTR gene variants and summarize results by population.
The analysis is conducted using a combination of Jupyter Notebook and supplementary data files.

Repository Contents

File/Folder	Description
Project6-Variant_Consequences.ipynb	Jupyter Notebook containing the full analysis workflow.
CFTR_pathogenic_samples.txt	Text file with pathogenic CFTR variant carriers.
CFTR_pathogenic_snp_result.txt	Processed SNP results for CFTR variants.
CFTR_rsIDs.txt	List of CFTR variant RSIDs.
CFTR_rs_numbers.txt	CFTR variant numbers for filtering.
CFTR_unique_HG_samples.txt	Unique CFTR carriers in the dataset.
Carrier_Population_IDs.txt	IDs of individuals grouped by population.
Pathogenic_CFTR_variants.txt	Text file with pathogenic CFTR variants.
resim2.png and resim3.png	Images/plots generated for visual analysis.
README.md	Project documentation.
Requirements

System Requirements
Operating System: Linux/Mac/Windows
Memory: ≥ 16GB
Software
Jupyter Notebook
Python ≥ 3.8
R ≥ 4.1
Tools:
bcftools for VCF processing
snpEff for variant annotation
Python Libraries
Install required libraries with:

pip install pandas numpy matplotlib seaborn
How to Run the Project

Clone the Repository
git clone https://github.com/ilahamusayeva93/Project6-VariantConsequences.git
cd Project6-VariantConsequences
Start Jupyter Notebook Launch the notebook interface:
jupyter notebook
Run the Analysis Notebook Open and execute:
Project6-Variant_Consequences.ipynb
This notebook contains all steps, including data reading, variant filtering, and population-level analysis.

Outputs

The results of the analysis are saved as text files:

CFTR_pathogenic_samples.txt: Identified carriers of CFTR variants.
Carrier_Population_IDs.txt: Population breakdown of carriers.
Pathogenic_CFTR_variants.txt: Annotated pathogenic variants.
Visual Outputs: resim2.png, resim3.png.
Key Results

Sickle Cell Variant Carriers
Example table of results:

Population	Carriers
GWD	26
YRI	30
ACB	9
CFTR Pathogenic Variants
Example population breakdown:

Population	Carriers
CEU	5
TSI	2
BEB	11
Acknowledgments

1000 Genomes Project for publicly available VCF data.
Tools: Python, R, bcftools, snpEff.
Developed by Ilaha Huseynli
