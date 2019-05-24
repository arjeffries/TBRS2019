Description of files:


R_script_450k_TBRS.txt
Script used for the manuscript entitled "Growth disrupting mutations in epigenetic regulatory molecules are associated with abnormalities of epigenetic aging"

CrossHybridisingProbesPriceORWeksberg.csv
This file contains a list of probes previously shown to cross hybridise with multiple regions of the genome (i.e. are non-specific).

AdditionalAnnotation450K_Price_Great_SNPsinProbeSequence.csv
This file is an amalgamation of additional annotation from the Price paper, Weksberg/Chen paper, GREAT, and Illumina.


Brief description of columns:

IlmnID
Name
AddressA_ID
AlleleA_ProbeSeq
AddressB_ID
AlleleB_ProbeSeq
Infinium_Design_Type
Next_Base
Color_Channel
Forward_Sequence
Genome_Build
CHR
MAPINFO
SourceSeq
Chromosome_36
Coordinate_36
Strand
Probe_SNPs
Probe_SNPs_10
Random_Loci
Methyl27_Loci
UCSC_RefGene_Name
UCSC_RefGene_Accession
UCSC_RefGene_Group
UCSC_CpG_Islands_Name
Relation_to_UCSC_CpG_Island
Phantom
DMR
Enhancer
HMM_Island
Regulatory_Feature_Name
Regulatory_Feature_Group
DHS


The above 38 columns are taken from the Illumina annotation (HumanMethylation450_15017482_v.1.2.csv) and should be fairly obvious what they are.


MAPINFO.1
MAPINFO.1.1
Probe_start
Probe_end
Target.CpG.SNP
n_target.CpG.SNP
SNPprobe
n_SNPprobe
HIL_CpG_class
HIL_CpG_Island_Name
n_bp_repetitive
AlleleA_Hits
AlleleB_Hits
XY_Hits
Autosomal_Hits
Closest_TSS
Closest_TSS_1
Distance_closest_TSS
Closest_TSS_gene_name
Closest_TSS_Transcript
SPOT_ID

These are from the Price annotation.


GREAT_anno
GREAT_anno1
GREAT_anno1_site
GREAT_anno2
GREAT_anno2_site

These are from GREAT.


Weksburg_CommonSNP_Af_within10bpSBE
Weksburg_RareSNP_Af_within10bpSBE
Weksburg_CommonSNP_Af_inProbeSeq
Weksburg_RareSNP_Af_inProbeSeq
Illumina_CommonSNP_Af_within10bpSBE
Illumina_RareSNP_Af_within10bpSBE
Illumina_CommonSNP_Af_inProbeSeq
Illumina_RareSNP_Af_inProbeSeq
Weksburg_CommonSNP_EuAf_within10bpSBE
Weksburg_RareSNP_EuAf_within10bpSBE
Weksburg_CommonSNP_EuAf_inProbeSeq
Weksburg_RareSNP_EuAf_inProbeSeq

These are columns I created taking the information from the Weksburg polymorphic probes lists and the most recent Illumina SNP annotation.
