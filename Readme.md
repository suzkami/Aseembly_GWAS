# A Pangenome-Scale Assembly-Native GWAS-to-Gene Framework

**Author:** SU ZHUO  
**Date:** 2026-03-24  
**Copyright:** © 2026

---

## Overview
This repository contains scripts and functions for the paper:

> *A pangenome-scale assembly-native GWAS-to-gene framework*

---

## Contents

### 1. Full k-mer GWAS Pipeline
A multi-thread accelerated pipeline for k-mer based GWAS analysis.

#### Modules
- **Matrix Build**  
  Construct k-mer presence/absence matrix  

- **Multi Split**  
  Split data for parallel processing  

- **Multi GWAS**  
  Perform GWAS in parallel  

- **Alignment to Pangenome**  
  Map significant k-mers to the pangenome  

---

### 2. R Functions
Utility functions for downstream statistical analysis and visualization.

#### Modules
- **Peak Detection**  
  Identify significant association peaks  

- **SP Detection**  
  Detect significant positions (SPs)  

- **SP Accumulation**  
  Aggregate SP signals  

- **Visualization**  
  - K-mer Manhattan Plot  
  - QQ Plot  

---

## Notes
- Designed for high-performance computing environments  
- Supports large-scale pangenome data analysis  
