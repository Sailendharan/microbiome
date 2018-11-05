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
Project Description|Qiime2 Analysis
Sample Count|95
Good Samples|90
Num observations|9263
Total count|6218793
Table density|0.064

Reference Database

16S

Report Generation Date

Mon Mar 13 14:40:17 2017

<!DOCTYPE html>
<html>
  <head>
    <meta charset='utf-8'>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>q2_demux : summarize</title>
    <link rel="stylesheet" href="./q2templateassets/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="./q2templateassets/css/normalize.css"/>
    <script src="./q2templateassets/js/child.js"></script>


  </head>
  <body>
    <div class="container-fluid">

<div class="row">
    <div class="col-lg-12">
        <h1>Demultiplexed sequence counts summary</h1>
        <table class="table table-striped table-hover">
            <tr><td>Minimum:</td><td>7</td></tr>
            <tr><td>Median:</td><td>30631.0</td></tr>
            <tr><td>Mean:</td><td>31744.8035714</td></tr>
            <tr><td>Maximum:</td><td>54421</td></tr>
            <tr><td>Total:</td><td>1777709</td></tr>
        </table>
    </div>
</div>


<div class="row">
    <div class="col-lg-12 text-center">
        <a href="demultiplex-summary.pdf">
            <img src="demultiplex-summary.png">
            <p>Download as PDF</p>
        </a>
    </div>
</div>


<div class="row">
    <div class="col-lg-12">
        <h1>Per-sample sequence counts</h1>
        <h4>Total Samples: 56</h4>
        <table border="0" class="dataframe table table-striped table-hover">
  <thead>
    <tr style="text-align: right;">
      <th>Sample name</th>
      <th>Sequence count</th>
    </tr>
    <tr>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Arl-soil-2-2-Plate1-D10</th>
      <td>54421</td>
    </tr>
    <tr>
      <th>Arl-soil-1-2-Plate1-D8</th>
      <td>53756</td>
    </tr>
    <tr>
      <th>Arl-soil-3-2-Plate1-D12</th>
      <td>52467</td>
    </tr>
    <tr>
      <th>Ant-soil-3-2-Plate1-E6</th>
      <td>47259</td>
    </tr>
    <tr>
      <th>WM-soil-1-2-Plate1-D2</th>
      <td>45735</td>
    </tr>
    <tr>
      <th>Ant-soil-3-1-Plate1-E5</th>
      <td>43049</td>
    </tr>
    <tr>
      <th>Ant-1-1-TSA-Plate1-C7</th>
      <td>42760</td>
    </tr>
    <tr>
      <th>WM-2-2-TSA-Plate1-B9</th>
      <td>41649</td>
    </tr>
    <tr>
      <th>WM-soil-2-1-Plate1-D3</th>
      <td>40642</td>
    </tr>
    <tr>
      <th>WM-soil-1-1-Plate1-D1</th>
      <td>39677</td>
    </tr>
    <tr>
      <th>WM-soil-2-2-Plate1-D4</th>
      <td>38939</td>
    </tr>
    <tr>
      <th>Ant-2-2-TSA-Plate1-C10</th>
      <td>37570</td>
    </tr>
    <tr>
      <th>Ant-soil-1-2-Plate1-E2</th>
      <td>37201</td>
    </tr>
    <tr>
      <th>Arl-soil-1-1-Plate1-D7</th>
      <td>36472</td>
    </tr>
    <tr>
      <th>Ant-soil-2-2-Plate1-E4</th>
      <td>36453</td>
    </tr>
    <tr>
      <th>Arl-soil-2-1-Plate1-D9</th>
      <td>36410</td>
    </tr>
    <tr>
      <th>Ant-2-3-PDA-Plate1-B4</th>
      <td>35736</td>
    </tr>
    <tr>
      <th>Ant-3-3-PDA-Plate1-B6</th>
      <td>35557</td>
    </tr>
    <tr>
      <th>WM-3-2-TSA-Plate1-B11</th>
      <td>35395</td>
    </tr>
    <tr>
      <th>WM-soil-3-1-Plate1-D5</th>
      <td>35310</td>
    </tr>
    <tr>
      <th>Arl-2-3-TSA-Plate1-C4</th>
      <td>34358</td>
    </tr>
    <tr>
      <th>Arl-3-1-TSA-Plate1-C5</th>
      <td>34329</td>
    </tr>
    <tr>
      <th>WM-3-3-TSA-Plate1-B12</th>
      <td>33152</td>
    </tr>
    <tr>
      <th>Arl-3-3-TSA-Plate1-C6</th>
      <td>32898</td>
    </tr>
    <tr>
      <th>Arl-1-2-TSA-Plate1-C2</th>
      <td>32043</td>
    </tr>
    <tr>
      <th>Arl-2-2-TSA-Plate1-C3</th>
      <td>31189</td>
    </tr>
    <tr>
      <th>Arl-1-1-PDA-Plate1-A7</th>
      <td>31038</td>
    </tr>
    <tr>
      <th>WM-2-3-TSA-Plate1-B10</th>
      <td>30813</td>
    </tr>
    <tr>
      <th>Ant-2-1-TSA-Plate1-C9</th>
      <td>30449</td>
    </tr>
    <tr>
      <th>Ant-1-1-PDA-Plate1-B1</th>
      <td>30231</td>
    </tr>
    <tr>
      <th>Ant-3-1-TSA-Plate1-C11</th>
      <td>29024</td>
    </tr>
    <tr>
      <th>Ant-3-1-PDA-Plate1-B5</th>
      <td>28880</td>
    </tr>
    <tr>
      <th>Arl-1-1-TSA-Plate1-C1</th>
      <td>28630</td>
    </tr>
    <tr>
      <th>Ant-3-3-TSA-Plate1-C12</th>
      <td>28613</td>
    </tr>
    <tr>
      <th>Arl-soil-3-1-Plate1-D11</th>
      <td>28493</td>
    </tr>
    <tr>
      <th>WM-soil-3-6-Plate1-D6</th>
      <td>28426</td>
    </tr>
    <tr>
      <th>Ant-1-2-TSA-Plate1-C8</th>
      <td>27909</td>
    </tr>
    <tr>
      <th>Ant-2-1-PDA-Plate1-B3</th>
      <td>27787</td>
    </tr>
    <tr>
      <th>Ant-soil-1-1-Plate1-E1</th>
      <td>27588</td>
    </tr>
    <tr>
      <th>WM-1-1-TSA-Plate1-B7</th>
      <td>27161</td>
    </tr>
    <tr>
      <th>Arl-3-2-PDA-Plate1-A11</th>
      <td>26939</td>
    </tr>
    <tr>
      <th>WM-2-3-PDA-Plate1-A4</th>
      <td>26819</td>
    </tr>
    <tr>
      <th>Ant-soil-2-1-Plate1-E3</th>
      <td>26399</td>
    </tr>
    <tr>
      <th>Arl-2-2-PDA-Plate1-A9</th>
      <td>26161</td>
    </tr>
    <tr>
      <th>Ant-1-3-PDA-Plate1-B2</th>
      <td>25407</td>
    </tr>
    <tr>
      <th>WM-3-3-PDA-Plate1-A6</th>
      <td>25347</td>
    </tr>
    <tr>
      <th>WM-3-1-PDA-Plate1-A5</th>
      <td>24073</td>
    </tr>
    <tr>
      <th>Arl-2-3-PDA-Plate1-A10</th>
      <td>24055</td>
    </tr>
    <tr>
      <th>WM-2-1-PDA-Plate1-A3</th>
      <td>23178</td>
    </tr>
    <tr>
      <th>WM-1-2-PDA-Plate1-A1</th>
      <td>22477</td>
    </tr>
    <tr>
      <th>WM-1-3-PDA-Plate1-A2</th>
      <td>21911</td>
    </tr>
    <tr>
      <th>Blank-2-Plate1-E8</th>
      <td>20318</td>
    </tr>
    <tr>
      <th>Arl-3-3-PDA-Plate1-A12</th>
      <td>20178</td>
    </tr>
    <tr>
      <th>WM-1-3-TSA-Plate1-B8</th>
      <td>19064</td>
    </tr>
    <tr>
      <th>Arl-1-3-PDA-Plate1-A8</th>
      <td>15907</td>
    </tr>
    <tr>
      <th>Blank-1-Plate1-E7</th>
      <td>7</td>
    </tr>
  </tbody>
</table>
        <a href="per-sample-fastq-counts.csv">Download as CSV</a>
    </div>
</div>

    </div>
  </body>
</html>


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
