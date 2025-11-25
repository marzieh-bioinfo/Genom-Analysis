# Genom-Analysis

This repository contains my bioinformatics workflows for genome and transcriptome analysis of *Streptomyces rimosus* strains R7 (wild-type) and HP126 (hyperproducer).

## Project overview
- De novo genome assembly and polishing (Flye + Pilon)
- Quality control of Illumina and Nanopore reads (FastQC, MultiQC)
- Genome comparison and functional annotation (QUAST, BUSCO, MUMmer, Prokka, eggNOG-mapper)
- RNA-seq differential expression analysis (DESeq2)

## Tools and technologies
- Programming: Python, Bash, R
- HPC: UPPMAX (Rackham, Slurm)
- Software: Flye, Pilon, Prokka, eggNOG-mapper, QUAST, BUSCO, MUMmer, DESeq2

## Repository structure
- `code/` – scripts and pipelines used in the analysis
- `author/` – project-related information and notes
- `out/` – selected output files and summary results (no raw data)

## Status
This project is part of my Bioinformatics MSc work and will be updated as I refine the analysis and documentation.
