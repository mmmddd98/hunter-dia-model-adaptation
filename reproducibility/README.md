# Benchmark FASTAs

The FASTA files used for the final benchmark searches are stored here.
The two TripleMix datasets share the same files. MG054 used a native-only
FASTA, without entrapment.

| Dataset | Native FASTA | Combined native/entrapment FASTA |
| --- | --- | --- |
| MD046–MD048 | [C. elegans](fastas/native/uniprotkb_proteome_UP000001940_2026_04_10.fasta) | [C. elegans with entrapment](fastas/entrapment/uniprotkb_proteome_UP000001940_2026_04_10.entrapment_rfixed_combined.fasta) |
| T_EX0097XX and T_Hamilton | [TripleMix](fastas/native/homo_sapiens_Arabidopsis_thaliana_escherichia_coli_fabian.fasta) | [TripleMix with entrapment](fastas/entrapment/homo_sapiens_Arabidopsis_thaliana_escherichia_coli_fabian.entrapment_rfixed_combined.fasta) |
| MG054 | [Human](fastas/native/UniProt_Proteome_Human_2026_01.fasta) | Not used |

Dataset configurations and training/test assignments are recorded in the
[workflow repository](https://github.com/mmmddd98/hunter-dia-workflows/tree/main/diaNN_pipline/datasets).
RAW and mzML measurement files are not included.
