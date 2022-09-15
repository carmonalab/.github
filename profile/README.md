## Cancer Systems Immunology laboratory

Working at the crossroads of data science, single-cell multi-omics, and cancer immunology,
we develop and apply computational methods to understand how our immune system responds to cancer and to identify 
new therapeutic targets and biomarkers. 

We are part of the [Department of Oncology](https://www.unil.ch/dof/carmona), Ludwig Institute for Cancer Research of the University of Lausanne, and the [Swiss Institute of Bioinformatics](https://www.sib.swiss/carmona-santiago). Our lab is located at the new [Agora Cancer Research Center](https://agora-cancer.ch/) in beautiful Lausanne, Switzerland.


<p align="center">
  <img height="300" src="https://github.com/carmonalab/.github/blob/master/profile/CSI_Toolkit.png">
</p>

**Overview of our lab's tools:**

* [UCell](https://bioconductor.org/packages/release/bioc/html/UCell.html): robust and scalable single-cell gene signature scoring, uses *positive* and *negative* genes and mitigates data sparsity by nearest neighbors smoothing. For easy retrieval and storing of signatures uses [SignatuR](https://github.com/carmonalab/SignatuR).

* [scGate](https://github.com/carmonalab/scGate): the tool for marker-based purification of cell populations. Use pre-defined *gating models* or create your own to purify a cell type or to classify into multiple cell types.

* [ProjecTILs](https://github.com/carmonalab/ProjecTILs): reference-based analysis framework, *1)* select or build your *reference map*, *2)* project new data into the map without alterning it. Then *3)* obtain high-resolution subtype classifications, *4)* explore how cell states in projected data deviate from the reference, and optionally, *5)* upgrade your reference to include novel cell states.

* [STACAS](https://github.com/carmonalab/STACAS): accurate integration (batch-effect correction) of single-cell transcriptomics data. Especially designed to integrate datasets with strong cell type unbalance. It can take advantage of prior knowledge to guide semi-supervised integration.

