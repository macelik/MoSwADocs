# Details of the sample files

**Aligned File**

The aligned fasta file (H5N1_H_HA_nr.afa) belongs to H5N1 human HA protein co-aligned with Avian H5N1 HA protein and it is adopted from the published article titled
"Dynamics of Influenza A (H5N1) virus protein sequence diversity" doi: 10.7717/peerj.7954
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7261124/


**CSV and JSON file**

Produced by MoSwA, the provided fasta file (H5N1_H_HA_nr.afa) was used as input with k-mer size parameter is set to 9, scanned for all motifs (index,major,minor and unique),
and threshold is set to 100. Below is the code to produce the same results from MoSwA stand alone.

```MoSwA.py -i H5N1_H_HA_nr.afa -m all -k 9 -t 100 -o test1```
