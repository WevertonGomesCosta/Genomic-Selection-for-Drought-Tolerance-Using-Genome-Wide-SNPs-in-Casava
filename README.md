
# Genomic Selection for Drought Tolerance

Welcome to the Genomic Selection for Drought Tolerance project website! This initiative by EMBRAPA Mandioca focuses on utilizing Genome Wide GBS and/or DART in Cassava to achieve drought tolerance through genomic selection.

## About the Project

This project aims to analyze the phenotypic data of Brazilian drought trials to evaluate the performance of various genotypes under drought conditions. The goal is to identify the genotypes that exhibit superior performance and resilience. The analysis follows a structured workflow, including data import and manipulation, exploratory data analysis, and genotype-environment analysis using mixed-effect models. This project details the estimation of Best Linear Unbiased Predictions (BLUPs) using mixed models, along with extensive Exploratory Data Analysis (EDA) and necessary manipulations to accurately estimate the BLUPs.

## Project Structure

### 1. [Exploratory Data Analysis (EDA)](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/phenotype.html)

We used packages such as DataExplorer, metan, and data.table to perform extensive exploratory data analysis on our dataset. The goal was to understand the data structure, identify missing values, and detect patterns that might influence the subsequent analyses.

### 2. [Genotype x Environment Interaction Analysis (GxE)](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/mixed_models.html)

The GxE analysis aims to evaluate the performance of genotypes across different environments to identify those with stable performance and high resilience. We used mixed-effect models to estimate the variance components and calculate BLUPs for each genotype.

### 3. [Genomic Wide Selection (GWS)](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS.html)

For GWS, we employed the original marker matrix, followed by necessary data manipulations to organize and prepare the matrix for model input. We used various models, including:

- [**RR-BLUP**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_RR-BLUP.html)
- [**G-BLUP (additive and additive-dominant)**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_G-BLUP.html)
- [**Bayes A**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_BayesA.html)
- [**Bayes B**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_BayesB.html)
- [**RKHS**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_RKHS.html)
- [**Random Forest**](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/GWS_RF.html)

(Note: Some models might be computationally intensive.)

### 4. [Clone Selection](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/clone_selection.html)

The clone selection analysis aims to identify the best genotypes for drought tolerance based on the GWS results. We used the BLUPs and genomic predictions to rank the genotypes and select the best-performing ones.

We will now obtain the joint results of all methods and compare them. Additionally, we will adopt a selection model to optimize the selection of cassava clones for EMBRAPA's cassava breeding program.

Our aim is to select clones with high GEBVs and high GETGVs, identifying clones with strong intrinsic potential as well as those that can be crossbred to produce high-potential hybrid clones.

## Study Highlights

- **Manuscript Access**: [Genomic Selection for Drought Tolerance Using Genome Wide SNPs in Cassava](https://doi.org/10.3389/fpls.2024.1483340)
- **Authors**: 
  - Weverton Gomes da Costa (Pós-Doutorando, Embrapa Mandioca e Fruticultura) - weverton.costa@ufv.br
