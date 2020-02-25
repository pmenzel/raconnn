# raconnn

A wrapper script for polishing a genome assembly in mutiple iterations using [racon](https://github.com/lbcb-sci/racon).

Requires `racon` and `minimap2` to be installed.

## Usage

The required arguments are:
* number of iteratons
* fastq file with sequencing reads that were used to assemble the genome
* fasta file with genome assembly

The polished assembly will be printed to STDOUT.

Example for two rounds of polishing:
```
raconnn 2 reads.fastq.gz assembly.fa > polished_assembly.fa
```


