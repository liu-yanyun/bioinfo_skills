cat > projects/covid19_genome_mutations/README.md << 'EOF'
# 🧬 Analyzing COVID-19 Genome Mutations

**Goal:** Compare a few SARS-CoV-2 complete genomes to identify mutations using free online tools (Clustal/MAFFT) and simple scripts.

## Steps
1) Download FASTA sequences (NCBI Virus / GISAID).
2) Align with Clustal Omega or MAFFT (web).
3) Inspect alignment for substitutions/indels and record positions.
4) (Optional) Visualize mutation positions/frequency (Python/MEGA/UGENE).
5) Interpret findings (e.g., Spike gene hotspots, known variants).

## Folders
- `data/` – input FASTA (example files only; avoid large data)
- `scripts/` – parsing/plotting utilities
- `results/` – alignment files, mutation tables, figures

## Outputs
- `results/alignment_result.*`
- `results/mutation_summary.csv`

EOF


