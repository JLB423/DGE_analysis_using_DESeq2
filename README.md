# DGE_analysis_using_DESeq2
Differential Gene Expression Analysis using DESeq2 of Breast Cancer RNA-seq Samples

The following report uses an RNA-seq dataset obtained from a study by Jiao, et al., (2019) to investigate the transcriptomic changes between breast cancer cells treated with NRDE2-targeting siRNA’s that cause NRDE2 depletion and control breast cancer cells not treated. The dataset contains 6 total fastq files from single end sequencing of 3 treated samples and 3 control samples.

I conduct the analysis by first running Salmon to get the transcript counts from RNA-seq data, then to detect differentially expressed genes I run an analysis on the counts using DESeq2 to compare the transcript expression between the two classes of samples, and to also characterize deferentially expressed genes that couple be potentially be impacted by knocking down NRDE2.

All file needed are located in supplementary zip

Reference:  Alan L. Jiao, Roberto Perales, Neil T. Umbreit, Jeffrey R. Haswell, Mary E. Piper, Brian D. Adams, David Pellman, Scott Kennedy, and Frank J. Slack (March 2019) Human nuclear RNAi-defective 2 (NRDE2) is an essential RNA splicing factor.RNA March 2019 25:352-363; Published in Advance December 11, 2018, doi:10.1261/rna.069773.118 
