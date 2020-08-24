---
layout: default
---

### Integrate Multi-Omics Data to Understand Mechanisms of Respiratory Diseases

Omics approaches have advanced our [understanding](https://pubmed.ncbi.nlm.nih.gov/28774304/) of complex respiratory diseases. However, our ability to generate omics data far exceeds our ability to interpret and validate findings with biological functionality. Most omics studies characterize the biological information from single modalities. Integrative analysis of multi-omics data provides insights underlying disease mechanisms beyond those from single-layered omics data.

Here, we use an asthma-related phenotype, glucocorticoid response, as a study model. Glucocorticoids are commonly used drugs for the treatment of asthma. They are known to exert anti-inflammatory effects via binding to glucocorticoid receptor (GR) transcription factors and modulating gene transcription. Some asthma patients have poor outcomes of glucocorticoid use which are likely conferred by genetic variants. Yet [recent](https://www.jacionline.org/article/S0091-6749(16)30596-6/fulltext) genome-wide association studies (GWAS) of glucocorticoid response found little evidence of common genetic variants having large genetic effects on this phenotype.

I have [identified](https://pubmed.ncbi.nlm.nih.gov/30694689/) cell type-specific gene expression changes in response glucocorticoids *in vitro*. My further question is that are there any genetic variants nominally associated with glucocorticoid response having cell type-specific biological functionality?

I have integrated GWAS data with publicly available transcriptomic data as well as epigenomic data of GR ChIP-Seq in various airway cell types. I have identified novel genetic variants located within GR-binding sites that influence patients' response to glucocorticoids via modulation of glucocorticoid and inflammatory signaling in airway cells.

![omics](imgs/research/omics.png)

This integration model can be extended to prioritize genetic variants that are nominally associated with other complex diseases and drug-response traits which will facilitate further mechanistic studies.

---


### Leverage Publicly Available Omics Data to Test Novel Hypotheses

With the advent of high throughput omics technologies, the volume of publicly available omics data has increased ever since. These data include experiments designed for comparing disease versus healthy individuals as well as cells exposed to drugs versus vehicle control. Leveraging existing datasets offers researchers a convenient and cost-effective avenue to test their novel hypotheses on disease mechanisms. However, public data are heterogeneous and not readily usable.

To facilitate the reproducible analysis of publicly available omics data, My colleagues and I have developed the pipelines [RAVED](https://github.com/HimesGroup/raved) for transcriptomic data analysis and [brocade](https://github.com/HimesGroup/brocade) for ChIP-Seq data analysis, and an online application [REALGAR](http://realgar.org/) that allows end-users to visualize results from omics data analysis and obtain integration results on-the-fly.

I [integrated](https://pubmed.ncbi.nlm.nih.gov/30815178/) analysis-ready results of asthma and asthma drug-related gene expression datasets and identified global and cell type-specific asthma and glucocorticoid-induced gene expression signatures. Here is a nice illustration by [Yoson](https://twitter.com/__yoson__) when I presented this work in IBI retreat.
![raved_illustration](imgs/research/raved.jpg)

I collaborate with molecular biologists to analyze and interpret their omics data using our open-source tools and pipelines which has made significant [scientific discoveries](https://www.pennmedicine.org/news/news-releases/2020/july/self-eating-process-of-stem-cells-may-be-the-key-to-new-regenerative-therapies).
