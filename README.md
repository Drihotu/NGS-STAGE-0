# NGS-STAGE-0
This repository contains my solution for the stage 0 Hackbio internship under the NGS fundamentals.
The project includes two projects:
✓ project 1: Introduction to Linus and bash for bioinformatics 
In this project I practiced both Linus and bash by applying my knowledge of both to the fna and gbk file.
- File and directory management ( moving and removing files)
- Downloading files from the web
-File manipulation 
• checking whether the sequence in the .fna file was mutant or wild type using grep.
• Extracting matching lines into a new file.
Counting the number of sequence lines in .gbk excluding the header.
• Extracting metadata such as sequence length (from the LOCUS tag), source organism (from the SOURCE tag), and a list of all genes (/gene=).
✓ project 2: Conda and bioinformatics tool
In this project, I worked with conda to create and manage environments and install core bioinformatics tools:

Created and activated a conda environment named funtools.

Installed widely used bioinformatics tools from the bioconda channel:

bwa – sequence alignment
blast – sequence similarity search
samtools – manipulation of SAM/BAM/CRAM files
bedtools – comparing and analyzing genomic regions
spades – genome assembly
bcftools – working with VCF/BCF variant files
fastp – FASTQ preprocessing and quality control
multiqc – aggregating QC and analysis reports
Verified each tool was properly installed and accessible inside the funtools environment.

This project gave me hands-on practice with setting up a reproducible bioinformatics environment, a key skill for any genomics project.