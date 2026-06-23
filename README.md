# BRCA12_vus_exploration_module1


## Scope

This storage contains an exploratory analysis of a precomputed ARIANE Module 1
BRCA1/2 coding SNV map. The dataset is intended for possible review-triage research and
method documentation. 


## Main Input And Output Files

| File | Rows | Notes |
| --- | ---: | --- |
| `variant_space_scan/outputs/brca_snv_manifest.csv` | 47547 | initial coding SNV manifest |
| `variant_space_scan/outputs/brca_snv_manifest.with_coordinates.local_full.csv` | 47547 | manifest with local coordinate mapping |
| `variant_space_scan/outputs/brca_snv_manifest.with_spliceai.ref_block_033_047_final.csv` | 47547 | manifest with reference-transcript SpliceAI scores |
| `variant_space_scan/outputs/brca_module1_full_snv_classification.csv` | 47547 | final Module 1 classification snapshot |

The GitHub export stores the final classification snapshot as
`data/brca_module1_full_snv_classification.csv.gz`.

## Final Snapshot Counts

Total variants: `47547`

### By Gene

| gene | count |
| --- | --- |
| BRCA1 | 16776 |
| BRCA2 | 30771 |

### By Generated Class

| class | count |
| --- | --- |
| 1 | 802 |
| 2 | 36150 |
| 3 | 8154 |
| 4 | 141 |
| 5 | 2300 |

### By Variant Type

| variant_type | count |
| --- | --- |
| initiation_codon | 18 |
| missense | 35241 |
| nonsense | 2397 |
| synonymous | 9891 |

### VUS Count

Class 3 VUS: `8154`

High SpliceAI variants, score >= 0.20: `1205`

### Applied Criteria Counts

| criterion | count |
| --- | --- |
| PM2_Supporting | 43166 |
| BP1 | 34855 |
| BS3 | 2528 |
| PVS1 | 2327 |
| PM5_PTC | 2241 |
| BP4 | 1404 |
| BP7 | 1404 |
| PP3 | 1060 |
| PS3 | 699 |
| BP5 | 514 |
| BS1_Supporting | 141 |
| BS1_Strong | 101 |
| PP4 | 58 |
| BA1 | 48 |
| PS1 | 7 |


