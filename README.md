#### Normalization of read counts using TPMs

It requires the original gtf file (genes.gtf) used for HT-seq-based read counts. The gtf file is used to calculate gene lengths based on their exons' lengths. Gene lengths are then used by the function normalize_by_TPM() to normalize read counts by TPMs.

The gtf file is located in the data folder.

