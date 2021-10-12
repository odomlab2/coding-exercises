# Spreadsheet exercise

In the `data` directory, you'll find two files: 

 - `E-GEOD-52564-query-results.csv` RNA-Seq Expression values as TPM (Transcripts Per Million) of cells in the mouse cerebral cortex 
 - `go-oxidate_phosphorylation.tsv` Gene list for the Gene Ontology (GO) term `oxidative phosphorylation` in mouse


## Task

Please use the available data to 

1) Extract the expression values for all genes that are part of the GO-term oxidative phosporylation and store it as 
   `expression_oxphos.csv`.
2) Filter the dataset from step (1) for genes with an expression with a TPM of 10 or higher. Then, calculate the mean expression for the group of extracted genes for each of the eight cell types and store it as
    `expression_oxphos_mean_per_celltype.csv`.


Depending on your preference, you may use R or Python as well as any publicy available packages to implement your solution. 

Your code will be evaluated for clarity and reproducibility. 

In case of questions, please don't hesitate to contact f.lammers@dkfz-heidelberg.de. 

## Additional information
List of cell types
```
"astrocyte",
"endothelial cell",
"microglia",
"mixture",
"myelinating oligodendrocytes",
"neuron",
"newly formed oligodendrocytes",
"oligodendrocyte precursor cells"
 ```