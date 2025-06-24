# Metagenomics and Cancer Genomics Projects

This repository contains two bioinformatics projects focused on distinct areas of genomics: cancer mutation profiling and soil microbiome analysis for antimicrobial resistance gene detection.

## 📁 Project 1: Cancer Mutation Analysis

**Objective:**  
Identify key mutations in a cancer dataset and classify them as either oncogenes or tumor suppressors.

**Tools & Resources Used:**
- [cBioPortal](https://www.cbioportal.org/) — for accessing and analyzing cancer mutation datasets
- [OncoKB](https://www.oncokb.org/) — for functional annotation and classification of cancer mutations

**Workflow Summary:**
- Selected a cancer dataset from cBioPortal.
- Extracted mutation data for relevant samples.
- Annotated and classified mutations using OncoKB.
- Identified and labeled genes as oncogenes or tumor suppressors.

---

## 📁 Project 2: Soil Microbiome AMR Gene Detection

**Objective:**  
Analyze a soil microbiome sample to identify antimicrobial resistance (AMR) genes and their mechanisms.

**Tools & Resources Used:**
- NCBI SRA — for accessing raw sequencing data
- `prefetch`, `fastq-dump` — for downloading FASTQ files
- **FastQC** — for read quality assessment
- **Trimmomatic** — for read trimming and cleaning
- **MEGAHIT** — for metagenome assembly
- **CARD (RGI)** — for identifying AMR genes and resistance mechanisms

**Workflow Summary:**
- Retrieved soil metagenomic data from NCBI SRA.
- Performed quality control and trimming on raw reads.
- Assembled reads into contigs using MEGAHIT.
- Submitted contigs to CARD for AMR gene identification and classification of resistance mechanisms.

