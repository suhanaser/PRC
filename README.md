# PRC
A pipline to charactarize PRC in D.magna and other related species
### Installation
To run this script you need Python 3 and the following dependencies: pandas, tqdm, glob, subprocess, getopt, Bio.Blast.Applications, and orffinder.
### Running the script
1. First you should create an empty directory for the output files
2. Then Run `PRC_pipeline.py` as follow:
```
PRC_pipeline.py -i <PRC_DNA_SEQUENCE> -d <DATABASE> -o <OUTPUT_DIR> -n <NUMBER_OF_THREADS>
<PRC_DNA_SEQUENCE>    The PRC sequence in fasta format
<DATABASE>            Protein database to use for the blastx search
<OUTPUT_DIR>          Directory where the final files will be saved
                      WARNING: All files in this directory will be deleted upon restart. Make sure you do not have any original files there.
<NUMBER_OF_THREADS>   The number of threads to be used in the analysis.
```
