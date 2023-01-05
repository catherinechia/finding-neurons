## Finding synapses
Last update: 2023-01-05

## Getting started
1. Install the necessary libraries/packages listed in each Jupyter notebook and install Jupyter (https://jupyter.org/install). Alternatively, create an Anaconda environment with the provided [environment.yml](/Tools/environment/20221231_findsyn_environment.yml) file.

2. Prepare 3 files (alternatively, you may download the demo files here: [Finding_synapses_datasets](https://drive.google.com/drive/folders/1Z9go5gfzBpbpvcCkiO7czPJgNspR1d-e?usp=sharing))
* An unannotated scRNA-seq
* An annotated scRNA-seq (if you intend to use scmap to annotate the unannotated scRNA-seq)
* A bulk RNA-seq derived from 1 or more samples

3. The Jupyter notebooks are labeled according to the flow chart. Start from the first notebook (A1_scmap_ReferenceForAnnotation_(Python).ipynb) or go directly to the notebook with steps of your interest. 

![Workflow](/fig/fig0_workflow.png?raw=true "Flow chart describing workflow")


## Report an issue
Found a bug? Please let us know by using the **Issues** tab above.


## Authors and affiliation
[Catherine Chia](https://github.com/catherinechia), [Amparo Roig Adam](https://github.com/amparora) and [Alessandro Moro](https://github.com/alemoro)
Functional Genomics (FGA) Department, Center for Neurogenomics and Cognitive Research (CNCR), Vrije Universiteit Amsterdam

## Reference
1. Chia, C. M., Roig Adam, A., & Moro, A. (2022). *In silico* multiple single-subject neural tissue screening using deconvolution on pseudo-bulk RNA-seq - a prototype. Bioinformatics and Systems Biology joint degree program. Vrije Universiteit Amsterdam and University of Amsterdam. 

2. Allen Institute for Brain Science (2004). Allen Mouse Brain Atlas, Mouse Whole Cortex and Hippocampus 10x. Available from mouse.brain-map.org. Allen Institute for Brain Science (2011).

3. Franzén, O., Gan, L. M., & Björkegren, J. L. M. (2019). PanglaoDB: a web server for exploration of mouse and human single-cell RNA sequencing data. Database : the journal of biological databases and curation, 2019, baz046. https://doi.org/10.1093/database/baz046

4. Kiselev, V. Y., Yiu, A., & Hemberg, M. (2018). scmap: projection of single-cell RNA-seq data across data sets. Nature methods, 15(5), 359–362. https://doi.org/10.1038/nmeth.4644

5. Zhang, Z., Luo, D., Zhong, X., Choi, J. H., Ma, Y., Wang, S., Mahrt, E., Guo, W., Stawiski, E. W., Modrusan, Z., Seshagiri, S., Kapur, P., Hon, G. C., Brugarolas, J., & Wang, T. (2019). SCINA: A Semi-Supervised Subtyping Algorithm of Single Cells and Bulk Samples. Genes, 10(7), 531. https://doi.org/10.3390/genes10070531
