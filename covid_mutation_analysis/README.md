# 🧬 Analyzing COVID-19 Genome Mutations

## Overview
This mini-project explores how SARS-CoV-2 genomes differ across countries by aligning and comparing their sequences.  
It aims to practice basic bioinformatics tasks like sequence retrieval, multiple sequence alignment (MSA), and mutation interpretation using free tools.

## Steps
1. **Download the Data**  
   - Source: [NCBI Virus](https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/)  
   - Search: *SARS-CoV-2 complete genome*  
   - Download 2–3 FASTA sequences from different countries (name them clearly, e.g., `china.fasta`, `ireland.fasta`, `usa.fasta`).

2. **Align the Genomes**  
   - Use [Clustal Omega](https://www.ebi.ac.uk/Tools/msa/clustalo/) or [MAFFT](https://mafft.cbrc.jp/alignment/server/).  
   - Upload all FASTA files → run alignment → download the aligned FASTA or view the MSA online.

3. **Identify Mutations**  
   - Compare aligned sequences and mark base differences (A→G, C→T, insertions/deletions).  
   - Note which gene or region they occur in (Spike, N, ORF1ab, etc.).

4. **Visualize the Mutations**  
   - Use **MEGA** or **UGENE** to open the alignment and inspect sites of variation.  
   - Optional: write a small Python script to count and plot mutation frequency per gene.

5. **Interpret Findings**  
   - Discuss which regions are more variable.  
   - Compare with known variants (e.g., Alpha, Delta, Omicron).

## Tools Used
- NCBI Virus / GISAID  
- Clustal Omega / MAFFT  
- MEGA / UGENE / Nextstrain (optional)  
- Python (for basic plotting)

## Learning Outcome
Understand viral genome evolution and practice handling FASTA data, alignment, mutation analysis, and result interpretation.

