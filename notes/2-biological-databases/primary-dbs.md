# NCBI Databases 

NCBI Database:
- nucleotide sequences
- protein sequences
- gene expression data
- structural information 
- https://www.ncbi.nlm.nih.gov/

GenBank:
- hosted by NCBI
- all publicly available nucleotide sequences
- on NCBI website, divided into "Gene", "Nucleotide" databases

PubMed:
- hosted by NCBI

BLAST:
- Basic Local Alignment Search Tool
- hosted by NCBI
- compare sequences against a vast db to find similarities and relationships


https://www.ncbi.nlm.nih.gov/:
- all databases tab
- PubMed, GenBank, BLAST


Retrieving an accession number from GenBank:
- go to GenBank db on the NCBI website
- use the search bar to find a specific gene or organism
- click on result to view the details of the sequence
- copy the accession number of the sequence 
- Locus tag can be considered an accession number
- Gene ID can be an accession number
- accession number exists at the level of protein and mRNA
    - this is in the General protein information (!!) within the Gene db page.
    - unique identifier for this protein within NCBI db.
    - 

Nucleotide > bzip1 > bzip arabidopsis
Gene > bzip arabidopsis > NP_199756.1 
Gene > bzip arabidopsis > NCBI Reference Sequences (RefSeq) > NP_199756.1 (link) > FASTA (link) >  


Now we can use BLAST to find a similar sequence to the accession number:
- BLAST > Protein BLAST >  NP_199756.1 (search) > Bread  Wheat (organism search) > show results in new window > BLAST (button) > download FASTA (completesequence) 

Downloading a sequence from GenBank:
- go to NCBI Reference Sequences (RefSeq)
- click link preceding accession number, this is its mRNA accession number
- NM_124322.3 > (this is the GenBank report) > FASTA (change file format) > Send to > File > Complete Record > Create File (button)
- you can download the mRNA, protein, and genomic sequences and save them into the same file. (I didn't do this). 

FASTA and GenBank:
- these are file formats
- FASTA: Sequence file
- GenBank: Report file


