## Purpose of this depository
This repository serve two purposes:
- Provide information on data source for module 1 problems
- Code depository for module 1

For each team, you should create a folder (team1, 2, etc) for your codes.

## Information about the data
The data we will use is from:
> [Gage et al. (2019) Multiple Maize Reference Genomes Impact the Identification of Variants by Genome-Wide Association Study in a Diverse Inbred Panel. Plant Genome 12:190069](https://dl.sciencesocieties.org/publications/tpg/abstracts/12/2/180069)

The data is deposited in [Dryad](https://datadryad.org/stash/landing/show?big=showme&id=doi%3A10.5061%2Fdryad.dk22g4h) that is available from:
> HPC: /mnt/

There are 34 files:
- data_dryad_readme_18Jan19.txt: Readme.
- 942_FPKM_B73_genes_w_feature.txt: Expression abundances of B73 v4 annotated genes (protein coding, tRNA, miRNA, and lincRNA genes).
- 942_FPKM_B73_RTAs.txt: Expression abundances of B73-derived novel transcripts.
- 942_FPKM_PH207_genes.txt: Expression abundances of PH207 annotated genes.
- 942_FPKM_PH207_RTAs.txt: Expression abundances of PH207-derived novel transcripts.
- 942_FPKM_PHJ89_genes.txt: Expression abundances of PHJ89 annotated genes.
- 942_FPKM_PHJ89_RTAs.txt: Expression abundances of PHJ89-derived novel transcripts.
- 942_FPKM_LOCONF_B73_genes_w_feature.txt: Expression abundances of B73 v4 annotated genes (protein coding, tRNA, miRNA, and lincRNA genes).
- 942_FPKM_LOCONF_B73_RTAs.txt: Expression abundances of B73-derived novel transcripts.
- 942_FPKM_LOCONF_PH207_genes.txt: Expression abundances of PH207 annotated genes.
- 942_FPKM_LOCONF_PH207_RTAs.txt: Expression abundances of PH207-derived novel transcripts.
- 942_FPKM_LOCONF_PHJ89_genes.txt: Expression abundances of PHJ89 annotated genes.
- 942_FPKM_LOCONF_PHJ89_RTAs.txt: Expression abundances of PHJ89-derived novel transcripts.
- B73_plus_RTAs_snp_matrix_995785.txt.gz: SNP calls B73 plus B73-derived novel transcripts.
- PH207_plus_RTAs_snp_matrix_988252.txt.gz: SNP calls PH207 plus PH207-derived novel transcripts.
- PHJ89_plus_RTAs_snp_matrix_995238.txt.gz: SNP calls PHJ89 plus PHJ89-derived novel transcripts.
- Trinity_B73_unmapped_transcriptome_assembly.fasta: B73-derived novel transcripts.
- Trinity_PH207_unmapped_transcriptome_assembly.fasta: PH207-derived novel transcripts.
- Trinity_PHJ89_unmapped_transcriptome_assembly.fasta: PHJ89-derived novel transcripts.
- B73_plus_RTAs_snp_matrix_imputed.zip: widiv_942g_979873SNPs_imputed_filteredGenos_withRTA_AGPv4.hmp.txt - Imputed SNP calls B73 plus B73-derived novel transcripts. SNPs on contigs that are not part of the 10 chromosomes are coded as being on chromosome 11, and SNPs on RTAs are coded as being on chromosome 12. widiv_942g_column_name_converter.txt - Converts genotype names between unimputed (column 'Original') and imputed (column 'NoSpaces').
- PH207_plus_RTAs_snp_matrix_imputed.zip: widiv_942g_971213SNPs_imputed_filteredGenos_withRTA_PH207ref.hmp.txt - Imputed SNP calls PH207 plus PH207-derived novel transcripts. SNPs on RTAs are coded as being on chromosome 11, and SNPs on contigs that are not part of the 10 chromosomes are coded as being on chromosome 12. widiv_942g_column_name_converter.txt - Converts genotype names between unimputed (column 'Original') and imputed (column 'NoSpaces').
- phj89_final_asm.no_desc.min_1k.fa: Genome assembly of Z. mays PHJ89 - min1kb scaffolds.
- phj89_final_asm.no_desc.fa: Genome assembly of Z. mays PHJ89 - all scaffolds.
- BUSCO_result.zip: Folder contains the output files from running BUSCO on the PHJ89 genome assembly.
- phj89_gene_models.hc.gff3: Generic feature format file (gff3) of high-confidence genes in PHJ89.
- phj89_gene_models.hc.cdna.fa: Transcript sequences (cDNA) of high-confidence genes in PHJ89.
- phj89_gene_models.hc.cds.fa: Coding sequences (CDS) of high-confidence genes in PHJ89.
- phj89_gene_models.hc.pep.fa: Protein sequences of high-confidence genes in PHJ89.
- phj89_gene_models.hc.func_anno.txt: Functional annotation of high-confidence genes in PHJ89.
- phj89_gene_models.lc.gff3: Generic feature format file (gff3) of low-confidence genes in PHJ89.
- phj89_gene_models.lc.cdna.fa: Transcript sequences (cDNA) of low-confidence genes in PHJ89.
- phj89_gene_models.lc.cds.fa: Coding sequences (CDS) of low-confidence genes in PHJ89.
- phj89_gene_models.lc.pep.fa: Protein sequences of low-confidence genes in PHJ89.
- phj89_gene_models.lc.func_anno.txt: Functional annotation of low-confidence genes in PHJ89.
