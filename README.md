# Influenza NGS Training (Using CLI): RCDC (29 January 2024)

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
Installation
```{shell}
conda install trim-galore
```
Run Trim-galore

### Assembly
Assemble the fastq files using denovo assembler SpAdes and BLAST (blastn) contigs for reference Assemby.
1. For denovo assembly: SpAdes

2. For reference based assembly: BBMap

Note: Mean Coverage:Minimum requirement for influenza is 1000

