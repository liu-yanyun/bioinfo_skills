# 🧬 COVID-19 Genome Mutations (Mini Project)

**Goal:** Download a few SARS-CoV-2 complete genomes, run an MSA (Clustal/MAFFT web), note substitutions/indels, and summarise mutations.

## Steps
1) Get 2–3 FASTA sequences (NCBI Virus / GISAID).
2) Run multiple sequence alignment (Clustal Omega / MAFFT web).
3) Save alignment to `results/alignment_result.aln` (or `.clustal`).
4) Create `results/mutation_summary.csv` with columns:
   `position,ref,alt,gene,note`
5) Add a short interpretation here (e.g., Spike region hotspots).
