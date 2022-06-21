# Oxford Planarian Bioinformatics Community

<img src="Asset 6OxfordPlanarian.png" alt="hi" class="inline"/>

Jakke Neiro<sup>1</sup> & Nathan Kenny<sup>2</sup>

1. Aboobaker lab, University of Oxford, <jakke.neiro@zoo.ox.ac.uk>

2. Solana lab, Oxford Brookes University, <nkenny@brookes.ac.uk>

This site includes code, files and other resources generated by the Oxford Planarian Bioinformatics Community.

## Annotation of the *Schmidtea mediterranea* genome
A new expression-driven annotation of the sexual planarian genome (*S. mediterranea*) was generated based on total RNA-seq data from this species. The annotation is based on 183 planarian RNA-seq samples (see the [sample list](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/Smed_annotation.list)), the [PlanMine sexual genome annotation (SMESG-high)](http://planmine.mpi-cbg.de/planmine/aspect.do?name=Gene%20Predictions), and the [PlanMine sexual genome (SMESG.1)](http://planmine.mpi-cbg.de/planmine/aspect.do?name=Genomes). 

[Notebook for annotation pipline](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/Annotation_Smed.ipynb)

[Download *S. mediterranea* annotation](https://github.com/jakke-neiro/Oxplatys/raw/gh-pages/Schmidtea_mediterranea_Oxford_v1.gtf.zip)

## Annotation of the *Dugesia japonica* genome
Similarly to the *S. mediterranea* annotation, the new expression-driven *D. japonica* annotation was generated based on 43 RNA-seq samples (see the [sample list](https://github.com/jakke-neiro/oxplatys/blob/gh-pages/Djap_annotation.list), the [Augustus-derived annotation](http://planarian.jp/index.html) and the [genome assembly](http://planarian.jp/index.html) at planarian.jp.  

[Download *D. japonica* annotation](https://github.com/jakke-neiro/Oxplatys/raw/gh-pages/Dugesia_japonica_Oxford_v1.gtf.zip)

## rds files of analyses presented in ACME paper
These files allow easy uploading to R of the analyses presented in the García-Castro et al. 2020 ACME paper.
[Download link](https://doi.org/10.6084/m9.figshare.13614605)

## Expression values
[Proportional expression values](https://github.com/jakke-neiro/Oxplatys/raw/gh-pages/FACS_prop.csv.gz)

## H3K27ac ChIP-seq data
[H3K27ac ChIP-seq bam file](https://drive.google.com/file/d/1IvlHBln6fEFcveq89WMXh0E9kgaF-99X/view?usp=sharing)

## ATAC-seq data
[ATAC-seq bam file](https://drive.google.com/file/d/19yd18GRDfdCMRyd1AxqG3F6nVDwxzfg6/view?usp=sharing)

## 2. Transcription factors
[2-1 Transcription factors identification](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/notebooks/2-1-Transcription-factors-identification.ipynb)

[2-2 Transcription factors literature review 2000-2009](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/notebooks/2-2-Transcription-factors-literature-2000-2009.ipynb)

[3-1 ChIP-seq QC and alignment](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/notebooks/3-1-ChIP-QCAlignment.ipynb)

[3-2 ChIP-seq filtering and analysis](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/notebooks/3-2-ChIP-FilteringAnalysis.ipynb)

[8-1 Transcription factor knockdown and RNA-seq](https://github.com/jakke-neiro/Oxplatys/blob/gh-pages/notebooks/8-1-TF-RNAseq.ipynb)

## Publications
### [Identification of enhancer-like elements defines regulatory networks active in planarian adult stem cells](https://www.biorxiv.org/content/10.1101/2022.02.03.479047v1)
Jakke Neiro, Divya Shridhar, Anish Dattani, Aziz Aboobaker

Planarians have become an established model system to study regeneration and stem cells, but the regulatory elements in the genome remain almost entirely undescribed. Here, by integrating epigenetic and expression data we use multiple sources of evidence to identify enhancer elements active in the adult stem cell populations that drive regeneration. We have used ChIP-seq data to identify regions with histone modifications consistent with enhancer identity and activity, and ATAC-seq data to identify accessible chromatin. Overlapping these signals allowed for the identification of a set of high confidence candidate enhancers predicted to be active in planarian adult stem cells. These enhancers are enriched for conserved transcription factor (TF) binding sites for TFs and TF families expressed in planarian adult stem cells. Foot-printing analyses provided further evidence that these potential TF binding sites are occupied in adult stem cells. We integrated these analyses to build testable hypotheses for the regulatory function of transcription factors in stem cells, both with respect to how pluripotency might be regulated, and to how lineage differentiation programs are controlled. Our work identifies active enhancers regulating adult stem cells and regenerative mechanisms.

### [ACME dissociation: a versatile cell fixation-dissociation method for single-cell transcriptomics](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02302-5)
Helena García-Castro, Nathan J. Kenny, Marta Iglesias, Patricia Álvarez-Campos, Vincent Mason, Anamaria Elek, Anna Schönauer, Victoria A. Sleight, Jakke Neiro, Aziz Aboobaker, Jon Permanyer, Manuel Irimia, Arnau Sebé-Pedrós & Jordi Solana

Single-cell sequencing technologies are revolutionizing biology, but they are limited by the need to dissociate live samples. Here, we present ACME (ACetic-MEthanol), a dissociation approach for single-cell transcriptomics that simultaneously fixes cells. ACME-dissociated cells have high RNA integrity, can be cryopreserved multiple times, and are sortable and permeable. As a proof of principle, we provide single-cell transcriptomic data of different species, using both droplet-based and combinatorial barcoding single-cell methods. ACME uses affordable reagents, can be done in most laboratories and even in the field, and thus will accelerate our knowledge of cell types across the tree of life.



