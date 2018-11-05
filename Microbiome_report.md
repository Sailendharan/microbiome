## **_Microbiome Analysis Report_**

UW Biotechnology Center Bioinformatics Resource Center 
Please direct questions to: **brc@biotech.wisc.edu**



 * * *

 1.  [Summary](#summary)
 2.  [Workflow](#workflow)
 3.  [Taxa Summary](#taxa_summary)
 4.  [Alpha Rarefaction](#a-rarefaction)
 5.  [Beta Diversity](#b-diversity)
 6.  [Phylogenetic Tree](#phylogeny)
 7.  [OTU Heatmap](#heatmap)
 8.  [Software](#software)

 * * *

 **Summary**

 **PI Name**|**Name**
:-----|:-----
Project Description|Qiime Analysis
Sample Count|95
Good Samples|90
Num observations|9263
Total count|6218793
Table density|0.064

Reference Database

16S

Report Generation Date

Mon Mar 13 14:40:17 2017

* * *

**Taxa Summary**

The count distribution for each level of taxa can be found in the "taxa\_summary" folder. L2(Class) to L7(Species)*   [View Full Interactive Taxa Summary](./taxa_summary/taxa_summary_plots/bar_charts.html)
![[Taxa Summary Plot]](./taxa_summary/taxa_summary_plots/charts/8h0y5jU6mr19l50dn0TsImZsiILWeB.png)  

* * *

**Alpha Rarefaction** ([documentation](https://docs.qiime2.org/2018.8/plugins/available/diversity/alpha-rarefaction/))

*   [View Alpha Rarefaction Plots](./a-rarefaction/alpha_rarefaction_plots/rarefaction_plots.html)

Metrics: Observed=Unique OTUs, Good's=Coverage, Shannon=Diversity, Chao=Richness

![[Observed]](a-rarefaction/alpha_rarefaction_plots/average_plots/observed_speciesSampleID.png)

![[Coverage]](a-rarefaction/alpha_rarefaction_plots/average_plots/goods_coverageSampleID.png)

![[Diversity]](a-rarefaction/alpha_rarefaction_plots/average_plots/shannonSampleID.png)

![[Richness]](a-rarefaction/alpha_rarefaction_plots/average_plots/chao1SampleID.png)

* * *

**Beta Diversity** ([documentation](http://qiime.org/scripts/beta_diversity_through_plots.html))

The normalized OTU file can be found in "b-diversity/otus\_sorted\_norm.taxa.txt"*   [View weighted unifrac PCoA plot](b-diversity/weighted_unifrac_emperor_pcoa_plot/index.html)
*   [View unweighted unifrac PCoA plot](b-diversity/unweighted_unifrac_emperor_pcoa_plot/index.html)

* * *

**Heatmap**

*   [View OTU Heatmap](./heatmap/otus_heatmap.png)

* * *

**Phylogenetic Tree**

*   [Right click and select "save as" to download tree](./otus/rep_set.tre)

* * *

**Software**

**Main Pipeline**|**v20170310**
:-----|:-----
QIIME|QIIME 1.9.0
OTU Clustering|Uclust
Quality Filtering|Usearch
Alignment|PyNAST
Taxonmy Assignment|RDP Classifier
Phylogeny Generation|FastTree

**Workflow Chart**

![[Workflow Chart]](Workflow.png)

Microbiota Analysis was performed by the UW biotechnology center using Quantitative Insights Into Microbial Ecology (QIIME)\[1\] version 1.9.1. Illumina sequencing reads were adapter and quality trimmed using the Skewer\[2\] trimming program to remove low quality (<Q25) bases and sequencing adapters. Reads shorter than 100 nucleotides after trimming were discarded. Flash\[3\] was used to merge paired end reads into amplicon sequences using a minimum overlap of 10 nucleotides. Amplicons were then PCR primer trimmed and quality filtered. Sequences were then clustered in OTUs using an open-reference OTU picking protocol based on 97% identity using UCLUST \[4\] against the Greengenes reference database\[5\]. Representative sequences (most abundant sequence in OTUs) were picked, aligned to GreenGenes Core reference alignment\[5\] using PyNAST\[6\]. Taxonomic assignments were associated with OTUs based on the taxonomy associated with the Greengenes reference sequence defining each OTU. UniFrac distances between samples were calculated using the Greengenes reference tree (ftp://greengenes.microbio.me/greengenes\_release/gg\_13\_5/gg\_13\_8\_otus.tar.gz). The resulting biom-formatted OTU table was filtered to remove singletons and OTUs that could not be aligned using PyNAST. Alpha rarefaction curves were calculated for all samples with a rarefaction upper limit of (median depth/sample count). Samples were removed from further characterization if they did not contain sufficient reads at a depth where the Good's coverage value for most samples was greater than 0.9. Beta diversity was calculated using wieghted and unweighted unifrac on OTU data leveled according to the lowest sample depth. An alternative normalization by CSS is also provided for additional downstream analysis\[7\].

1.  Caporaso, JG et al. (2010). QIIME allows analysis of high-throughput community sequencing data. Nature Methods, doi:10.1038/nmeth.f.303
2.  Hongshan J, Rong L, Shou-Wei D, and Shuifang Z. (2014) Skewer: a fast and accurate adapter trimmer for next-generation sequencing paired-end reads. BMC Bioinformatics. 15:182. DOI: 10.1186/1471-2105-15-182.
3.  Magoc T & Salzberg S. (2011). FLASH: Fast length adjustment of short reads to improve genome assemblies. Bioinformatics 27:21 , 2957-63.
4.  Edgar, R.C. (2010) Search and clustering orders of magnitude faster than BLAST, Bioinformatics 26(19), 2460-2461. doi: 10.1093/bioinformatics/btq461
5.  DeSantis TZ, et al. (2006) Greengenes, a chimera-checked 16S rRNA gene database and workbench compatible with ARB. Appl Environ Microbiol 72:5069�5072.
6.  Caporaso, JG et al. (2010) PyNAST: a flexible tool for aligning sequences to a template alignment. Bioinformatics 26: 266-267. DOI 10.1093/bioinformatics/btp636.
7.  Paulson, JN, et al. (2013) Differential abundance analysis for microbial marker-gene surveys. Nature Methods

* * *

Please acknowledge BRC in your manuscript or presentation. If you think our analysis contributes to your research intellectually please consider authorship for our bioinformaticians.
