# Codon Mapping

## Task Description
We want you to write a python script which takes as input

1. A GTF genome annotation file
2. A genomic location in the format ```chromosome:position:strand```

It should return a value which says whether the position is within a protein coding region or not, and if it is, which position within the codon it is in.

## Relevant details
The position in the location is "1 indexed" so the first base of a chromosome is position 1, not position 0

The strand identifier is either ```+``` for top strand, or ```-``` for bottom strand

The format of the output can be up to you, but it needs to be clear whether the position matches or not.  The position within the codon should be 1,2 or 3.

## Data provided
We have given you ```Drosophila_melanogaster.BDGP6.54.114.gtf.gz``` which is an Ensembl GTF file for Drosophila, which you can use as an example input.