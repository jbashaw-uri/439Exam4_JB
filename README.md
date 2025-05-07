# 439Exam4_JB
This repository contains code that can be used to read a genomic sequence (a string of characters A,T,G, and C) and return counts of k-mers within the sequence and the frequency of each character following each k-mer. The script should be given an input file containing the genome sequence, the desired k-mer length (or k value), and the name of an output file.



The files within this repo are written for Python3 and utilize the `sys` Python module.

### Files:
- `BIO439_Exam4_JB.py` the script that writes the frequencies of substrings and their following-characters to a given output file
-  `Informational Document` a document containing responses to the three prompts given in the assignment guidelines

### How to use:
In the command line, run:

    python3 <input_file> <k-value> <output_file>

The k-value should be an integer.
