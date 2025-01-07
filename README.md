# Genomic Selection for Drought Tolerance

Welcome to the Genomic Selection for Drought Tolerance project website! This initiative by EMBRAPA Mandioca focuses on utilizing Genome Wide GBS and/or DART in Cassava to achieve drought tolerance through genomic selection.

## About the Project

This project aims to analyze the phenotypic data of Brazilian drought trials to evaluate the performance of various genotypes under drought conditions. The goal is to identify the genotypes that exhibit superior performance and resilience. The analysis follows a structured workflow, including data import and manipulation, exploratory data analysis, and genotype-environment analysis using mixed-effect models. This project details the estimation of Best Linear Unbiased Predictions (BLUPs) using mixed models, along with extensive Exploratory Data Analysis (EDA) and necessary manipulations to accurately estimate the BLUPs.

## Project Structure

### 1. Exploratory Data Analysis (EDA)

We used packages such as DataExplorer, metan, and data.table to perform extensive exploratory data analysis on our dataset. The goal was to understand the data structure, identify missing values, and detect patterns that might influence the subsequent analyses.

### 2. Genotype x Environment Interaction Analysis (GxE)

The GxE analysis aims to evaluate the performance of genotypes across different environments to identify those with stable performance and high resilience. We used mixed-effect models to estimate the interaction effects and calculate BLUPs for each genotype-environment combination.

### 3. Genomic Wide Selection (GWS)

For GWS, we employed the original marker matrix, followed by necessary data manipulations to organize and prepare the matrix for model input. We used various models, including:

- **RR-BLUP**
- **G-BLUP (additive and additive-dominant)**
- **Bayes A**
- **Bayes B**
- **RKHS**
- **Random Forest**

(Note: Some models might be computationally intensive.)

## Study Highlights

- **Manuscript Access**: [Optimizing drought tolerance in cassava through genomic selection](https://doi.org/10.3389/fpls.2024.1483340)
- **Authors**: 
  - Weverton Gomes da Costa (Pós-Doutorando, Embrapa Mandioca e Fruticultura) - weverton.costa@ufv.br

## Visit the Project Website

For detailed information and resources, visit our [Project Website](https://wevertongomescosta.github.io/Genomic-Selection-for-Drought-Tolerance-Using-Genome-Wide-SNPs-in-Casava/).
