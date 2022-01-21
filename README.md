# Data submission for yeast rRNA modification paper
Uploading Fast5's to ENA, Fastq's and corresponding modification calls to SRA/GEO.

## ENA submission
* create project, samples and runs
* [documentation](https://ena-docs.readthedocs.io/en/latest/index.html)
* submit filled out samples template and runs template [here](https://www.ebi.ac.uk/ena/submit/webin/)
* upload data: `lftp webin2.ebi.ac.uk -u Webin-#####`
* mput <all files>

## GEO Submission
* fill out sequencing template
* `mput *
*` https://www.ncbi.nlm.nih.gov/geo/info/submissionftp.html