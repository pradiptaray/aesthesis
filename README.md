# aesthesis
AESTHESIS : Algorithmic Elucidation of Sensory Transcriptomic landscapes for rapid hypotHESIS testing

AESTHESIS is a collection of scripts to rapidly post process count data for transcriptome assays 
It is developed in UT Dallas in the Pain Neurobiology Research Group, led by Theodore Price and Greg Dussor
Author : Pradipta Ray
Please email pradiptaray@utdallas.edu or theodore.price@utdallas.edu for commercial use or derivatibe works.

code.zip
The code to generate sample statistics from TPM values is present in code.zip . It requires tab separated TPM tables named 'human_tpm.txt' and 'mouse_tpm.txt' as input.

gene_family_lists.zip
This file contains lists of human and mouse gene families that we profiled in the paper.

human_microarray_data.zip
This file contains all normalized probeset ids, probeset intensities, probeset and gene names (when possible to annotate) for all human microarray datasets we analyzed in the paper.

human_rnaseq_data.zip
This file contains tab separated file for GENCODE annotation and relative abundances for all human genes (TPM in Sheet 1, uqTPM in Sheet 2) for all analyzed human tissue. It also contains human to mouse gene orthology mapping, entropy and enrichment scores, and hDRG:hTN abundance ratio.

mouse_rnaseq_data.zip
This file contains tab separated file for GENCODE annotation and relative abundances for all mouse genes (TPM in Sheet 1, uqTPM in Sheet 2) for all analyzed human tissue. It also contains human to mouse gene orthology mapping, entropy and enrichment scores, and mDRG:mOlfactory Epithelium abundance ratio.

gumy_et_al_genes_drg_tn_expr.txt
This file contains the unique human ortholog gene list based on the genes detected in sensory neuronal axons from adult rat, based on the Gumy et al (RNA, 2011) paper.

spinal_cord_microarray_data.zip
This file contains the microarray probe values for the human spinal cord datasets that were additionally contrasted with the DRG, TG, NHSC and FIBRO datasets.

permission_kegg.pdf
This file contains written (email) permission from Kanehisa Laboratories to use the Kegg pathway diagram in publication.
