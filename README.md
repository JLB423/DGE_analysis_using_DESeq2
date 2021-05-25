# DGE_analysis_using_DESeq2
Differential Gene Expression Analysis using DESeq2 of Breast Cancer RNA-seq Samples

The following report uses an RNA-seq dataset obtained from a study by Jiao, et al., (2019) to investigate the transcriptomic changes between breast cancer cells treated with NRDE2-targeting siRNA’s that cause NRDE2 depletion and control breast cancer cells not treated. The dataset contains 6 total fastq files from single end sequencing of 3 treated samples and 3 control samples.

I conduct the analysis by first running Salmon to get the transcript counts from RNA-seq data, then to detect differentially expressed genes I run an analysis on the counts using DESeq2 to compare the transcript expression between the two classes of samples, and to also characterize deferentially expressed genes that couple be potentially be impacted by knocking down NRDE2.



