🧬SARS-CoV-2 NGS Data Preprocessing Pipeline

This repository provides a step-by-step pipeline for preprocessing and analyzing SARS-CoV-2 next-generation sequencing (NGS) data. 
The workflow includes quality control, trimming, alignment, and visualization using common bioinformatics tools.





🔧Tools used:

All tools are open source.

Galaxy: https://usegalaxy.in

FastQC: https://www.bioinformatics.babraham.ac.uk/projects/fastqc/

Trimmomatic: http://www.usadellab.org/cms/?page=trimmomatic

BWA: http://bio-bwa.sourceforge.net/

SAMtools: http://www.htslib.org/

IGV: https://software.broadinstitute.org/software/igv/






⚙️Requirements

FastQC – Quality control of raw reads

Trimmomatic – Trimming adapters and low-quality bases

BWA – Short-read aligner

SAMtools – File manipulation (SAM ↔ BAM, sorting, indexing)

IGV – Interactive Genome Viewer for visualization

SARS-CoV-2 reference genome (FASTA format, e.g., from NCBI)








📂Input Data


SRR33976241.fastq.gz

GCF_009858895.2_ASM985889v3_cds_from_genomic.fna = Reference genome

GCF_009858895.2_ASM985889v3_cds_from_genomic.fna.fai

GCF_009858895.2_ASM985889v3_cds_from_genomic.fna

aligned_reads_sorted.bam.bai

aligned_reads_sorted.bam








📊Result

SRR33976241_fastqc.html

Galaxy22-[Trimmomatic on Trimmomatic on SRR33976241.fastq.gz].fastqsanger]
