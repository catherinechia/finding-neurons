# F. CIBERSORTx
Last update: 2022-12-31

## Outline
1. Upload reference scRNA-seq and bulk RNA-seq to CIBERSORTx
2. Create signature matrix
3. Impute cell fractions
4. Export results


#### Upload reference scRNA-seq and bulk RNA-seq to CIBERSORTx
![Upload_files](/fig/fig1_upload.png?raw=true "Upload reference and bulk RNA-seq")
1. Upload (pseudo) bulk RNA-seq as **Reference Sample**
2. Upload reference scRNA-seq as **Single Cell Reference Matrix**

#### Create signature matrix
![Create_signature_matrix](/fig/fig2_create_sigmtx.png?raw=true "Create signature matrix")
1. Click on the **Create Signature Matrix** button to select the module
2. Select the uploaded reference scRNA-seq
3. Input a name for the signature matrix this function is about to create
4. Click **Run**

#### Impute cell fractions
![Impute_cell_fractions](/fig/fig3_impute_cell_fractions.png?raw=true "Impute cell fractions")
5. Click on the **Impute Cell Fractions** button to select the module
6. Select the created signature matrix from steps 1-4
7. Select the uploaded bulk RNA-seq file
8. Select a number of permutations for significance analysis
9. Click **Run**

## Export results
![Workflow](/fig/fig4_results.png?raw=true "Export results")
A. Column of sample names
B. Cell-type proportions in each sample
C. Scroll down and you will find a stacked barplot showing the cell-type compositions per sample
D. Results export options


## Reference
1. Chia, C. M., Roig Adam, A., & Moro, A. (2022). *In silico* multiple single-subject neural tissue screening using deconvolution on pseudo-bulk RNA-seq - a prototype. Bioinformatics and Systems Biology joint degree program. Vrije Universiteit Amsterdam and University of Amsterdam. 

2. Newman, A. M., Liu, C. L., Green, M. R., Gentles, A. J., Feng, W., Xu, Y., Hoang, C. D., Diehn, M., & Alizadeh, A. A. (2015). Robust enumeration of cell subsets from tissue expression profiles. Nature methods, 12(5), 453–457. https://doi.org/10.1038/nmeth.3337

3. Allen Institute for Brain Science (2004). Allen Mouse Brain Atlas, Mouse Whole Cortex and Hippocampus 10x. Available from mouse.brain-map.org. Allen Institute for Brain Science (2011).

