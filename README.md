
## Bioinformatics Training Material

Below, you will find the links to the lectures and Google Colab notebooks for the practical modules. 

### Practical Modules with Google Colab Notebooks:

- [Notebook A - Processing raw scRNA-seq data](https://colab.research.google.com/github/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/Colab_notebooks/Modules/KEMRI_workshop_Notebook_A_quality_control_and_normalization.ipynb):
_Processing raw single-cell sequencing data (scRNA-seq) is a first step in the whole pipeline analysis of scRNA-Seq experiments. Depending on the library preparation method used, the RNA sequences will be acquired either from 3’ ends (or 5’ ends) of the transcripts (10X Genomics, CEL-seq2, Drop-seq, inDrops) or from full-length transcripts (Smart-seq). The choice of a specific method will depend entirely on the biological question and the downstream analysis to be implemented from a count matrix. In this notebook we will cover theoretical and practical steps in setting up from raw sequences (reads)to count matrix analysis pipelines, as well as explore the basic output of the Cell Ranger tool._
[**Lecture: Preprocessing**](https://github.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/lectures/Module_1_preprocessing.pptx).

- [Notebook B - Quality Control, Exploratory Analysis, Data Normalization, Clustering, Differential expression in scRNA-seq experiments](https://colab.research.google.com/github/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/Colab_notebooks/Modules/KEMRI_workshop_Notebook_B_batch_correction_and_integration.ipynb):
_This notebook guides you through the initial steps of scRNA-seq data analysis, including data importing and organization, filtering, and preliminary visualization, facilitating the interpretation of cellular heterogeneity. We will learn how to dentify the set of features (genes/transcripts) that show distinct patterns of expression when comparing different conditions._
[**Lecture: Preprocessing**](https://github.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/lectures/Module_2_quality_control_and_normalization.pptx) and [**Lecture: Clustering and cell annotation**](https://github.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/lectures/Module_3_cell_annotation.pptx).

- [Notebook B - Integrating single-cell transcriptomes from multiple samples](https://colab.research.google.com/github/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/Colab_notebooks/Modules/KEMRI_workshop_Notebook_B_batch_correction_and_integration.ipynb):
_With the increasing complexity of single-cell data, the integration of multiple datasets has become common. However, it is crucial to account for batch effects resulting from technical and biological variations to perform accurate analyses. These batch effects can stem from differences in sample handling, experimental protocols, sequencing platforms, as well as biological factors like the donor's genetic background and tissue origin. 
By employing computational methods to address these variations when comparing multiple samples, unwanted sources of variation can be eliminated, allowing researchers to focus on biologically meaningful signals. The process of removing batch effects involves making two important choices: selecting the appropriate method and parameterization, and determining the batch covariate. While the parameters are specific to the chosen method, the selection of the batch covariate depends on the goal of the integration task. This notebook will cover the key concepts and methods related to data integration and batch-effect correction, followed by hands-on activities that illustrate the integration of multiple datasets using methods from Seurat and Harmony._
[**Lecture: Batch Correction and Data Integration**](https://github.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/lectures/Module_4_batch_correction.pptx).

- [Notebook C - Immune receptor profiling and CITE-Seq in Single-Cell Analysis](https://colab.research.google.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/Colab_notebooks/Modules/KEMRI_workshop_Notebook_C_immune_receptors.ipynb) : 
_In this module, participants will explore the application of immune receptor profiling for understanding immune responses._[**Lecture: Immune receptor profiling**](https://github.com/ShalekLab/KEMRI_Kilifi_2024_workshop/blob/main/lectures/Module_5_BCR_background_and_10x_analysis.pptx).


******
## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
