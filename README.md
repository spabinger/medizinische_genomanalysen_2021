# Medizinische Genomanalysen 2021
Material and information about the lecture "Medizinische Genomanalysen" 2021


## Grading
* 50% assignments
* 50% student projects & presentation

## Assignment Overview
* Link for assignment will be sent out
* Clone the classroom repository of each assignment
* Each student needs to work on his/her assignment (no team work)
* When done, commit and push the results to your github repository
* All assignments need to be completed by **16.05.2021**

## Python packages
* Biopython (http://biopython.org/)
* pybedtools (https://daler.github.io/pybedtools/)
* Bed tutorial - (http://quinlanlab.org/tutorials/bedtools/bedtools.html)
* NCBI (http://biopython.org/DIST/docs/api/Bio.Entrez-module.html)
* pybam (https://github.com/JohnLonginotto/pybam)
* pysam (http://pysam.readthedocs.io/en/latest/usage.html)
* cyvcf2 (https://github.com/brentp/cyvcf2)
* pyvcf (http://pyvcf.readthedocs.io/en/latest/)
* HGVS - does only work with Python2! (https://hgvs.readthedocs.io/en/master/)
* pyfaidx
* pyranges - efficient comparison of genomic intervals in Python (https://pubmed.ncbi.nlm.nih.gov/31373614/)



## Assignment 1
* ``conda install --channel conda-forge --channel bioconda pybedtools``
* Genome coverage - https://daler.github.io/pybedtools/autodocs/pybedtools.bedtool.BedTool.genome_coverage.html?highlight=coverage#pybedtools.bedtool.BedTool.genome_coverage
* https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token
* Added pandas to available packages in the autograder setup

## Assignment 2
* Added pandas to available packages in the autograder setup

## Assignment 3
* Added pandas to available packages in the autograder setup
* **get_list_of_genes()** do not return the list of genes but the number of elements in the list of genes


## Student projects

### Exercise - Clinical sequencing

#### Your TODOs
1. Perform 6 analysis steps (if possible) using FASTQ files (subset your file to speed up the analysis)
2. Per group present the selected software and the performed analysis
   * Software: 10min 
   * Results: 10min


#### Perform the following steps (if supported)
1. Data Import – take FASTQ files from:
   * Illumina: ftp-trace.ncbi.nih.gov/giab/ftp/data/AshkenazimTrio/HG002_NA24385_son/NIST_Illumina_2x250bps/reads/  
   * Ion Torrent: (Only for Ion Reporter) ftp-trace.ncbi.nih.gov/giab/ftp/data/AshkenazimTrio/HG002_NA24385_son/ion_exome/ 
   * Requirement: human, genome (no RNASeq, methylation, …)
2. Quality Control & QC Report
3. Mapping
4. Variant Calling (SNV, Indel)
5. Variant Annotation
6. Interpretation & Decision Making

#### Student groups 
1. Illumina basespace  --  https://basespace.illumina.com/home/index 
   * Kerndl	Martina
   * Kollros	Dominik
   * Szaffich	Sarah
   * Szechenyi	Philipp
   * Umlauf	Ellen

2. Maser  --  http://cell-innovation.nig.ac.jp/maser/index_en.html
   * Cozzarini Helena
   * Kaiser	Manfred
   * Salzmann	Martina
   * Senk	Stefan   
   * Waldherr	Monika

3. Galaxy  --  https://main.g2.bx.psu.edu/ 
   * Binnyei	Christian
   * ~~Lin	Grace~~
   * Polzer	Daniel
   * Wanka	Philipp
   * Zechmeister	Alexander

4. Chipster  --  http://chipster.csc.fi/ 
   * Cirovic	Natasa
   * Kotzian	Andreas
   * Schinogl	Eric 
   * Tatzber	Julia
   * Zhang	Lijuan

5. GenePattern  --  https://cloud.genepattern.org/
   * Brunner	Bernd   
   * Singer	Benedikt
   * Terzijski	Alexander
   * Tucek	Lisa


*Backup: https://www.basepairtech.com/ , https://ionreporter.thermofisher.com , https://www.strand-ngs.com , (https://www.dnanexus.com/)*








