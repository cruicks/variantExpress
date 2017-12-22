# variantExpress
Collection of scripts to run and intersect GATK and SNiPR variant pipelines from RNA-seq data

GATK_RNAseq.groovy - Bpipe script to execute The GATK Best Practices for variant calling on RNAseq (https://gatkforums.broadinstitute.org/gatk/discussion/3892/the-gatk-best-practices-for-variant-calling-on-rnaseq-in-full-detail)
SNPiR.groovy - Bpipe script to execute SNPiR reported by Piskol, Ramaswami and Ramaswami (doi: 10.1016/j.ajhg.2013.08.008. by Piskol R, Ramaswami G, Li JB. Reliable identification of genomic variants from RNA-seq data. Am J Hum Genet. 2013;93(4):641-651.)
intersectGATKandSNPIR_RNAseq_variant_files.py - Python script to find overlap between SNPiR and GATK variants
ANNOVAR_vcf_variant_filtering.groovy – Bpipe script to annotate RNA-seq variants with ANNOVAR
