# Assessment-4-25SEPT
PART-1
# Analysis of Gene Expression and Growth Data

This repository contains an RMarkdown workflow for the analysis of gene expression and growth data. The analysis explores nucleotide and amino acid composition, gene expression values, growth patterns, and statistical comparisons across datasets.

# Features

# Gene Expression Analysis

Downloading and processing expression data from TSV files.

Calculating mean expression across samples.

Identifying top genes with highest expression.

Filtering genes with low mean expression values.

Visualization of expression distributions using histograms.

# Growth Data Analysis

Downloading growth data from CSV files.

Calculating mean and standard deviation of tree circumference across sites.

Comparing growth over time (2005–2020) between northeast and southwest regions.

Visualization with boxplots.

Statistical testing using t-tests to determine significance of growth differences.

# DNA and Protein Sequence Analysis

Downloading complete coding DNA sequences for E. coli and Clostridium baratii.

Counting coding sequences and total coding DNA length.

Calculating sequence length distributions (mean, median, total).

Frequency analysis of nucleotides and amino acids with bar plots.

Codon usage bias analysis using RSCU values.

Identification of over- and under-represented protein sequence k-mers.

# Repository Contents

# PART-1_myscript.Rmd

Gene expression analysis.

Growth data analysis (mean, SD, boxplots, t-tests).

# PART-2_myscript.Rmd

DNA sequence analysis of E. coli and Clostridium baratii.

Coding sequence count and length analysis.

Nucleotide and amino acid composition analysis.

Codon usage bias analysis with bar plots.

K-mer frequency analysis in protein sequences.

# Figures

Bar plots for nucleotide and amino acid composition.

Histograms for mean gene expression.

Boxplots comparing tree growth at different sites and times.

Volcano-style codon usage bias plots.

# Tables

Summary tables of gene expression (mean values).

Coding DNA sequence counts and lengths.

Top codons and k-mers for both organisms.

# Prerequisites

This project requires R (>= 4.0) and the following R packages:

# Core Packages

prettydoc

tidyverse (dplyr, ggplot2)

knitr

seqinr

# Statistical & Bioinformatics Packages

DESeq2

RUVSeq

PCAtools

EnhancedVolcano

ComplexHeatmap

mitch

msigdbr

Biostrings

# Visualization & Plotting

ggrepel

gplots

ggpubr

enrichplot

cowplot

RColorBrewer

circlize

viridis

# Authors

Developed by Prerna Dhakla
