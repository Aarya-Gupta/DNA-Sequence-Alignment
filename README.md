# DNA Sequence Alignment using Dynamic Programming

This repository contains Python code for performing global and local alignment of DNA sequences using dynamic programming. The main objective of this project is to implement dynamic programming to find the best local and global alignments for given DNA sequences.

## Overview

### Code
The code provided performs global alignment of DNA sequences using dynamic programming. It utilizes a scoring matrix and traceback to find the optimal alignments.

### DNA Sequences
The DNA sequences used for alignment are:
1. Sequence 1: GATGCGCAG
2. Sequence 2: GGCAGTA

### Scoring Scheme
The scoring scheme used for alignment is as follows:
- Match: +2
- Mismatch: -3
- Gap: -1

### Files
- `Global_Alignment.ipynb`: Python script containing the code for global alignment.
- `Local_Alignment.ipynb`: Python script containing the code for local alignment.

### Implementation Details
- The code initializes the sequences and scoring scheme.
- It then constructs a scoring matrix using dynamic programming.
- The traceback algorithm is used to find optimal alignments.
- Optimal alignments, along with their scores, are printed.

## Usage
To use the code:
1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Run the `Global_Alignment.ipynb` and `Local_Alignment.ipynb`  script.

## Results
Upon execution, the code will print:
- The scoring matrix.
- All possible optimal alignments with their scores.

## Conclusion
This project demonstrates the implementation of dynamic programming for DNA sequence alignment. Following the instructions and completing the code can efficiently align DNA sequences and obtain optimal alignments.

For any questions or issues, please contact [Aarya Gupta](mailto:aarya22006@iiitd.ac.in).
