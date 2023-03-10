# seqedit
Interactive nucleotide sequence editor. You can choose two methods with using -c or -t options which are reserved for sequence conversion to complementary strand, and trimming 5' and 3' region in the sequence, respectively. Multi-fasta format is acceptable.

Usage:

    seqedit [option] [fasta file]
    
    options
        -c: convert to complementary strand mode
        -t: sequence trimming mode

Requirement
    - BioPython package
