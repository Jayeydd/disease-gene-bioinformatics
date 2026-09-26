# Title: Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar

## Name: Jade Angela B. Suan

## Assigned Gene: FBN1

## Associated disease: Marfan syndrome

## Genome assembly: GRCh38/hg38

## Date: 2026-09-25

---------------

## Part A. Create Your Github Activity Record


---------------

## Part B — Gene Location in UCSC Genome Browser

| Item | Recorded Information |
|---|---|
| Official gene symbol | FBN1 |
| Full gene name | Fibrillin 1 |
| Chromosome | 15 (q21.1) |
| Genome assembly | GRCh38/hg38 |
| Genomic coordinates | chr15:48,408,313 – 48,645,709 |
| DNA strand | − (minus/reverse strand) |
| Approximate gene size | ~237.4 kbp (237,397 bp) |

**Screenshot 1 — Gene Location:**
![Gene Location](images/01_gene_location.jpg)

-----------------
## Part C — Gene Structure: Exons, Introns, Transcripts

| Item | Answers |
|---|---|
| Annotation track used | MANE Select Plus Clinical / RefSeq Curated |
| Selected transcript | NM_000138.5 (MANE Select) |
| Number of exons | 65 |
| Multiple isoforms visible? | Yes — GENCODE shows 5 filtered; RefSeq has separate rows too |
| Difference between Exon and Intron | Exons are the coding regions of a gene that carry the instructions for making proteins, while introns are the non-coding regions that sit between exons and get cut out |
| Intron vs exon length | Introns are much longer — exons are small boxes separated by long lines |

**Screenshot 2 — Gene Structure:**
![Gene Structure](images/02_gene_structure.jpg)

---------

## Part D — Annotation Tracks, ClinVar Variants & Conservation

| Item | Answers |
|---|---|
| Annotation tracks displayed | MANE Select Plus Clinical, RefSeq Curated, GENCODE V50, OMIM Genes, ClinVar Variants, ClinVar SNVs, ClinVar interp, Cons 100 Verts |
| ClinVar variants visible | Yes — numerous red bars and red circles indicate pathogenic/likely pathogenic variants associated with FBN1 |
| Conservation track name | Cons 100 Verts — 100 vertebrates Basewise Conservation by PhyloP |
| Conservation pattern | Strongest conservation peaks align directly with exon positions; intron regions show low/flat conservation |
| Are some regions more conserved than others? | Yes — exons are highly conserved across vertebrates; introns show very little conservation |
| Why exons are more conserved | Exons encode the protein sequence — changes here disrupt fibrillin-1 function and are selected against during evolution. Introns are removed during splicing so their sequence matters less |
| Biological significance | Red pathogenic variants fall in highly conserved regions → confirms these sequences are functionally critical. Mutations here cause Marfan syndrome by impairing fibrillin-1 structure or function |

**Screenshot 3 — ClinVar & Conservation Tracks:**
![ClinVar and Conservation Tracks](images/03_tracks.jpg)

---
## Part E — ClinVar Variant Details

| Item | Recorded Information |
|---|---|
| Selected ClinVar Variant ID | VCV000146334 |
| Genome Assembly | GRCh38 / hg38 |
| Genomic Coordinates | chr15:47460844–52494222 |
| Cytogenetic Location | 15q21.1–q21.2 |
| Gene Symbol | FBN1 (Fibrillin 1) |
| Variant Classification | Copy Number Variant — **Deletion / Loss** |
| Variant Size | ~5,033,379 bp (5.0 Mb) |
| Clinical Significance | **Pathogenic** |
| Associated Phenotype | Marfan syndrome |
| Mechanism of Pathogenicity | Large gene deletion removes substantial portion of FBN1 → haploinsufficiency — insufficient functional fibrillin-1 → weakened extracellular matrix → Marfan features |
| Inheritance Pattern | Autosomal Dominant — one altered copy causes disease |
| Submission/Review Status | Reported Feb 2011; 1 submitter; classification: Pathogenic |

**Screenshot 4 — ClinVar Variant Details:**
![ClinVar Variant VCV000146334](images/04_clinvar_variant.jpg)

