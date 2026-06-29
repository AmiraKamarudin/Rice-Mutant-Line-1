
## Supplementary Data
This repository contains the supplementary materials and Bash scripts used to analyse whole-genome sequencing data from a Malaysian mutant rice. All analyses were run on Windows Subsystem for Linux (WSL 2). WSL is a Linux environment on the Windows machine that runs Ubuntu 24.04.3 LTS. 

## Citation
**Kamarudin, S. A. A.**, Hasan, N., Faiz, A., Zainal Abidin, N. (2026). Whole-genome resequencing of an acute gamma-mutagenised *Oryza sativa*: a resource for discovering the landscape of genomic variants related to bacterial leaf blight resistance. *Data in Brief*.

## Raw Data
The raw reads are publicly available at the NCBI Sequence Read Archive repository under the accession number [SRR37260596](https://www.ncbi.nlm.nih.gov/sra/?term=SRR37260596).

## Methods and Tools
 This repository stores the supplementary materials and Shell scripts used to analyse whole-genome sequencing data obtained from Illumina NovaSeq 6000. The sequencing data was quality assessed with FastQC v0.12.1, trimmed with Trimmomatic v0.39, read mapped with BWA MEM v0.7.17, read deduplicated with samtools markdup v1.19.2, variant called with bcftools mpileup v1.19, and functionally annotated with SnpEff v5.2.1.


------
