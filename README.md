# CancerMigration-scripts
self learning GATK pipelines and shell scripts

changeName: input a two columes file, first colume to be the initial names and second the names to change.

CancerMigration-target sequencing handling pipeline:

1 targetSequencing.sh: bwa-samtools-picardtools-pileup

2 getCombinedPileup.pl: input position file for SNPs, get the right information from pileup file

3 MutationCalling.pl: count mutation number

4 totalMutcall.pl: grab useful information from the count files to be one file, which should be the final file to be used
