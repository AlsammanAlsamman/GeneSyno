# GeneSyno
GeneSyno, a simple, versatile and reliable tool that can be used to extract gene information from human genome data given the synonymous name of the gene. GeneSyno was written using C and Python programming languages and could easily be integrated into a different pipeline.

GeneSyno requires data files ( which already exist in data folder)

chrom-list.txt		=	Human chromosomes accessions
GENES-ACCESSIONS.txt	=	Genes accessions and names information
GRCh38_genomic.gff		=	Genome annotation in GFF format
GRCh38_protein.faa		=	Human genome protein sequences


#To RUN GenoSyno
python3 GeneSyno.py genelist_test.txt

#You can rebuiled C tool using inside lib folder
gcc find-gene-in-gff.c -o find-gene-in-gff
