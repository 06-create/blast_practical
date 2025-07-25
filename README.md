
My First DNA Search Using BLAST

By Purva Gaikwad  
B.Tech Biotechnology | Aspiring Computational Biologist


As a part of my first bioinformatics project, 
I explored BLAST — a powerful DNA search tool — to see how a DNA sequence can be matched to known organisms.

BLAST (Basic Local Alignment Search Tool) is like **Google for DNA**.
You give it a DNA or protein sequence, and it finds similar sequences in known organisms.
I used NCBI BLAST to find out what organism shares the DNA sequence I gave it. It was a piece of the COX1 gene.
My sequence matched with 100% identity to a bird species — Amazona collaria. E-value was 3e-04, so the match was strong!

What I Learned
- How to use BLAST
- How to understand results (E-value, percent identity, query coverage)
- How genes can be similar across species


My Input Sequence (COX1 Gene)

>Human_COX1_Full
ATGACACAATCATAAAGATATTGGGTTTGATCCTGGCCTCCTGCTCATTCATTATAATTTTCTTGAGGGGAATTATATTCGA...






I also built a Python tool using Biopython to run and parse BLAST results that:
- Runs BLAST using Biopython
- Saves and parses results
- Prints the top 5 matches from NCBI

code: (https://github.com/06-create/blast_tool_python)


