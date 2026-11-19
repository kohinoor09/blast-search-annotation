# blast-search-annotation# BLAST Search and Hit Annotation

## What I did
Searched a query sequence against a public database using NCBI BLAST and interpreted the best hits.

## Query
- Sequence: human insulin (UniProt P01308), file `query.fasta`

## Search parameters
- Tool: NCBI BLAST (web), blastp
- Database: Swiss-Prot
- Matrix: BLOSUM62
- E-value threshold: 0.05
- Max target sequences: 100
- Date run: 20 Nov 2026
- RID: <paste RID>

## Files
- `blast_output.txt`: full BLAST text output
- `hits.csv`: hit table
- `annotation_table.md`: annotated top matches
- `blast_screenshot.png`: results page

## Interpretation
<5-8 lines from Step 5>

## Decisions
<1-2 lines>

## How to reproduce
1. Open blast.ncbi.nlm.nih.gov → Protein BLAST
2. Paste `query.fasta`, choose Swiss-Prot, keep default settings
3. Click BLAST and compare with `hits.csv`
