# Downsample BAM files

## Task Description
We would like a method to downsample a bam file, either a series of commands for exising programs or a newly written program.

The inputs to provide would be:

1. The name of an existing BAM file
2. The name of a new output BAM file
3. The number of reads to be sampled from the file
4. Whether the reads should be selected only from uniquely mapped reads in the input data

The read selection should be completely random, imposing no biases on the data which is selected.

## Relevant details
This method should work for any BAM file.

If the data is paired end then it should select the relevant number of read pairs (so a target of 100 would actually yield 100 pairs, or 200 actual reads in the output)

The output should retain the same order of reads as the input.


## Data provided
No data is provided for this task.  If you want a suitable test dataset then you could download a mapped BAM file from ENCODE.  Something like [this BAM file](https://www.encodeproject.org/files/ENCFF048QSZ/@@download/ENCFF048QSZ.bam) should be suitable.