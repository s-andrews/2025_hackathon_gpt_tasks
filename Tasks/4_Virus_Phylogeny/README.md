# Influenza Phylogenetic Tree

## Task Description
You have been provided with a fasta file of 501 hemagglutinin protein sequences from influenza virus sequences isolated in the UK.

We would like you to make a phylogentic tree out of these sequences.  The tree should be coloured by the serotype of the virus.  A serotype for influenza looks like ```HxNy``` where x and y are numbers, eg ```H5N1, H1N1``` etc.  The serotype is at the end of the fasta header line for each entry.  If you have an incomplete entry (eg just H3) then this sequence should be removed.

## Relevant details
You can use any combination of programs to acheive this task.  It will likely require an initial alignment followed by tree construction.

You can choose the format of tree.

Ideally the final file should be in an editable file format (SVG, PDF, WMF etc)


## Data provided
A single multi-fasta file of protein sequences, ```human_influenza_ha_proteins.fa``` is provided.