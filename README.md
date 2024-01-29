# Influenza Sequencing training: RCDC (29 January 2024)

## Quality Check and trimming
### Quality Check
FastQC
Installation
```{shell}
Conda create -n FastQC
conda install -c bioconda fastqc
```
Run FastQC
```{shell}
fastqc *.fastq.gz -o FastQC_result
```
### Trimming 
Trim-galore
### Assembly
Assemble the fastq files using denovo assembler SpAdes and BLAST (blastn) contigs for reference Assemby.
For denovo assembly: SpAdes
For reference based assembly: BBtools


