# brb-libprep
These codes were used to compare and analyze the automated and manual amplicon library preparation methods.

Authors: Brooke R. Benz, Eglantina Lopez-Echartea, Briana K. Whitaker, Thomas Baldwin, and Barney A. Geddes.

Run codes in this order:
2022b_Nextseq_DADA2.Rmd > Runs through the DADA2 pipeline to generate ASVs and assign taxonomy to the NextSeq results.

2022b_Nextseq_MergingPSobject.Rmd > Makes the phyloseq object for the NextSeq samples by using the otu table and taxa table from DADA2.

2022b_Nextseq_SCRuB.Rmd > Removes contaminants using the positive and negative controls to statistically estimate the contaminating sequences.

2022b_Miseq_DADA2.Rmd > Runs through the DADA2 pipeline to generate ASVs and assign taxonomy to the MiSeq results.

2022b_Miseq_MergingPSobject.Rmd > Makes the phyloseq object for the MiSeq samples by using the otu table and taxa table from DADA2.

2022b_Miseq_SCRuB.Rmd > Removes contaminants using the positive and negative controls to statistically estimate the contaminating sequences.

2022b_Miseq_Nextseq_MergingPSobjects.Rmd > Merges the MiSeq and NextSeq phyloseq objects for further analysis.

2022b_Miseq_Nextseq_RarefactionCurves.Rmd > Generates rarefaction curves and rarefies the data.

2022b_Miseq_Nextseq_ReadDepthDistribution.Rmd > Plots read depth distribution per sample and gives mean, variance, and skewness values for each plot.

2022b_Miseq_Nextseq_BetaDiversity.Rmd > Beta diversity analysis before and after rarefaction comparing sequencing platforms and library preparatoin methods.

2022b_Miseq_Nextseq_Beta_Linear_Dissimilarity.Rmd > Comparison of beta diversity dissimilarity means within and between treatments.

2022b_Miseq_Nextseq_AlphaDiversity.Rmd > Correlation of alpha diversity metrics between library preparation methods.

Automated_Manual_Quantification_Comparison.Rmd > Correlation of manual and automated quantification methods.

Automated_Manual_LibPrep_ConsumableComparison.Rmd > Comparison of consumable costs per step for each library preparation method.
