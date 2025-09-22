## Cancer Systems Immunology laboratory

We study patterns of variation across cancer patients to identify general principles of the immune system regulation during tumor progression.
We combine innovative data science with high-throughput single-cell and spatial omics technologies to reveal biological insight and develop predictive models of disease progression and response to treatment.

We are part of the [Department of Pathology and Immunology](https://www.unige.ch/medecine/pati/) of UNIGE, and the [Swiss Institute of Bioinformatics](https://www.sib.swiss/carmona-santiago). Our lab is located at the [Centre Médical Universitaire (CMU)](https://www.unige.ch/medecine/en/contacts-acces/contact) of the Faculty of Medicine, in Geneva.


<p align="center">
  <img height="150" src="https://github.com/carmonalab/.github/blob/master/profile/CSI_toolkit_simple.png">
</p>

**Overview of our lab's tools:**

* [GeneNMF](https://github.com/carmonalab/GeneNMF): unsupervised discovery of gene programs in omics data by non-negative matrix factorization (NMF). It can be especially useful to extract recurrent gene programs in cancer cells, which are otherwise difficult to integrate and analyse jointly.

* [SignatuR](https://github.com/carmonalab/SignatuR): a database of useful gene signatures for single-cell analysis. It also provides utilities to store and interact with gene signatures.

* [UCell](https://github.com/carmonalab/UCell): robust and scalable single-cell gene signature scoring, uses *positive* and *negative* genes and mitigates data sparsity by nearest neighbors smoothing. For easy retrieval and storing of signatures we recommend [SignatuR](https://github.com/carmonalab/SignatuR).

* [scGate](https://github.com/carmonalab/scGate): the tool for marker-based purification or classification of cell populations. Use pre-defined *gating models* or create your own to purify a cell type or to classify into multiple cell types.

* [STACAS](https://github.com/carmonalab/STACAS): accurate integration (batch-effect correction) of single-cell transcriptomics data. Its semi-supervised mode takes advantage of prior cell type knowledge to guide integration. To assess quality of integration, [scIntegrationMetrics](https://github.com/carmonalab/scIntegrationMetrics) provides multiple useful metrics.

* [ProjecTILs](https://github.com/carmonalab/ProjecTILs): reference-based analysis framework, *1)* select or build your *reference map*, *2)* project new data into the map without altering it. Then *3)* obtain high-resolution subtype classifications, *4)* explore how cell states in projected data deviate from the reference, and optionally, *5)* upgrade your reference to include novel cell states.

* [SPICA](https://spica.unil.ch/): web portal to explore our immune cell reference maps and to project into them your own data

For stable releases of our tools, including automated build/install checks on multiple architectures, please visit our [R-universe repository](https://carmonalab.r-universe.dev/builds).
