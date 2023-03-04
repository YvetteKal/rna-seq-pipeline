# rna-seq-pipeline

this project hwlped familiarize with RNAseq data analysis from quality control up to read counts estimation.
The number of samples in the project is 1 but can be adapted to many samples to get a read counts matrix.
This is the last command to retreave some rows from the subcounts output and put them in another file:
cat demo_featureCounts.txt | cut -f1,7 | less > new_file.txt
