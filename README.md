# FastQC

**Fastqc is a quality control tool for high throughput sequence data.**

**Tool Installtion** : Tool can be installed using a link  ( link : https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) 

It is very important to check the quality of the data before we shall do any analysis on it. As data quality will decide whether or not the data is good enough for further analysis.
FastQC tool will provide informations like 

1. Basic information like Filename, File type ,Encoding, Total Sequences, Sequences flagged as poor quality ,Sequence length ,%GC .( Table is provided below for the reference) .

![image](https://github.com/user-attachments/assets/5c491237-54f9-42c8-acc5-424571a2e20d)

3. Per base sequence quality.
4. Per tile sequence quality.
5. Per sequence quality scores
6. Per base sequence content
7. Per sequence GC content
8. Per base N content
9. Sequence Length Distribution
10. Sequence Duplication Levels
11. Overrepresented sequences
12. Adapter Content

**Input - Query input files are FASTQ (.fq/.fastq ) - which is standard out of NGS platforms.**

**Output of the tool will be a .html with all the information ( Output example file (html) is provided here for reference.)**
