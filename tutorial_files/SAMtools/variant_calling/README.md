##SAMtools variant calling tutorial
These are the complete files for the [SAMtools variant calling tutorial](http://biobits.org/samtools_primer.html), written by Ethan Cerami and distributed under the [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/deed.en_US).

Download this zip file and move the zipped file to your scratch directory on the cluster prior to unzipping.

The contents of this zipped folder are as follows:
```
samtools_primer-master
|-- README.md
|-- figs
|   |-- ngs_overview.ai
|   |-- ngs_overview.png
|   |-- sam_format_example.graffle
|   |   |-- data.plist
|   |   `-- image1.png
|   |-- sam_format_example.png
|   |-- steps_overview.ai
|   |-- steps_overview.png
|   |-- tview.png
|   |-- tview2.png
|   `-- vcf.png
`-- tutorial
    |-- align_to_genome.sh
    |-- alignments
    |   |-- sim_reads_aligned.bam
    |   |-- sim_reads_aligned.sam
    |   |-- sim_reads_aligned.sorted.bam
    |   `-- sim_reads_aligned.sorted.bam.bai
    |-- generate_simulated_reads.sh
    |-- genomes
    |   |-- NC_008253.fna
    |   |-- NC_008253.fna.fai
    |   `-- NC_008253_1K.fna
    |-- identify_variants.sh
    |-- indexes
    |   |-- e_coli
    |   |-- e_coli.1.bt2
    |   |-- e_coli.2.bt2
    |   |-- e_coli.3.bt2
    |   |-- e_coli.4.bt2
    |   |-- e_coli.rev.1.bt2
    |   `-- e_coli.rev.2.bt2
    |-- simulated_reads
    |   `-- sim_reads.fq
    `-- variants
        |-- sim_variants.bcf
        `-- sim_variants.vcf
'''
