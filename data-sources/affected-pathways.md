#### Affected pathways

This data type contains pathway information on biochemical reactions sourced from the following sources:

##### Reactome

The [Reactome](http://www.reactome.org/) database manually curates and identifies reaction pathways that are affected by pathogenic mutations.

##### SLAPenrich

[SLAPenrich](https://saezlab.github.io/SLAPenrich/) \(Sample-population Level Analysis of Pathway enrichments\) is a novel statistical framework for the identification of significantly mutated pathways, at the sample population level, in large cohorts of cancer patients. It is based on a Poisson binomial model that takes into account the length of blocks of exons in genes within each pathway, and the background mutation rate of the analysed cohort of patients. We include in our Open Targets Platform the data obtained using SLAPenrich on somatic mutations from the The Cancer Genome Atlas \(TCGA\) across 25 different cancer types and a collection of pathway gene sets from Reactome. See [Iorio et al 2018](https://www.nature.com/articles/s41598-018-25076-6) for more details.

##### PROGENy

[PROGENy](https://saezlab.github.io/progeny/) \(Pathway RespOnsive GENes\) is a linear regression model that calculates pathway activity based on consensus gene signatures obtained from perturbation experiments. We use PROGENy \([Schubert et al 2018](https://www.nature.com/articles/s41467-017-02391-6.epdf?author_access_token=16QkzhJ3OA3qJDqBw_GvGdRgN0jAjWel9jnR3ZoTv0NBFLUVI-ebH2AmtFlR1ykSPIho7ETJXL7VqZFC4zGtU0BaeoZncGrwx3ZW24lfVqvbSWqsQKaUXFTi_c-4pgcpX-1qerWYlkG6sha8rhrnMg%3D%3D)\) for the systematic comparison of pathway activities between normal and primary samples from The Cancer Genome Atlas \(TCGA\). We include in our Open Targets Platform sample-level pathway activities inferred from RNA-seq for 9,250 tumour and 741 normal TCGA samples from 14 tumour types, and compute differential pathway activities between matched normal and tumour samples. We cover the following pathways: androgen, EGFR, estrogen, hypoxia, JAK.STAT, MAPK, NFkB, PI3K, TGFb, TNFa, Trail, VEGF, WNT, and p53.

