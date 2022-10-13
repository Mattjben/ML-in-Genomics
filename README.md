# ML-in-Genomics
Genetics and understanding the functional components of the human genome, proteins, epigenetic modifications etc. has immense potential for developing possible therapeutics and diagnostic methods for otherwise untreated conditions such as cancer and heart disease. Since most diseases and biological functions in the human body arise because of the complex interaction between hundreds of genes, the environment and its effect of gene expression and the billions of DNA bases pairs all of which are uniquely arranged, as we continue to map out human genomes data science is essential for extracting the desired genomic information from all this data.

Although there is a large scope for the possible applications of this field, the role primarily involves looking for insights into the data. One possible project would be to use genome data across a large sample space of individuals with and without a specific disease or disorder to identify DNA sequences, genes and/or proteins which are distinctly different between the two groups. This analysis could have applications in diagnostics of genetic conditions or intensifying genetics factors which contribute to diseases, it could also aid in drug discovery, target therapies, gene therapy, genome editing etc.


## DATASET 1 : Mice Protein Expression data set

URL: https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression 
This Dataset contains 1080 observations with 82 features, 77 of which indicate the protein expression level of an individual protein in each mouse. The other 5 features provide the unique ID for each mouse and indicate which of the 8 classes each sample belongs to according to their respective genotypes, behaviour, and treatment. These classes are segregated based on whether the sample is trisomic (contains three of a particular chromosome), whether the sample has been stimulated to learn and whether memantine has been given to the sample. The classes are designated as:  

•	c-CS-s: control mice, stimulated to learn, injected with saline 
•	c-CS-m: control mice, stimulated to learn, injected with memantine  
•	c-SC-s: control mice, not stimulated to learn, injected with saline  
•	c-SC-m: control mice, not stimulated to learn, injected with memantine  
•	t-CS-s: trisomy mice, stimulated to learn, injected with saline  
•	t-CS-m: trisomy mice, stimulated to learn, injected with memantine  
•	t-SC-s: trisomy mice, not stimulated to learn, injected with saline  
•	t-SC-m: trisomy mice, not stimulated to learn, injected with memantine  

The main aim of Dataset 1 would be to identify the subset of proteins that are discriminate between the classes which would therefore indicate the proteins associated with the disorder, learning task and those effected by the memantine drug in the aims to better understand the drug interactions and possible insights into future drug development. 

## DATASET 2 : Mice Protein Expression data set

URL: https://archive.ics.uci.edu/ml/datasets/gene+expression+cancer+RNA-Seq 

This dataset contains 801 observations with 20531 features all of which correspond to the expression level of an RNA sequence/gene of human tumours, the target variable being the type of tumour sequenced.  The tumour types are designated as: 

•	BRCA: Breast invasive carcinoma 
•	KIRC:  Kidney renal cell carcinoma 
•	COAD: Colon adenocarcinoma 
•	LUAD: Lung adenocarcinoma 
•	PRAD: Prostate adenocarcinoma 



Dataset 2 can be used to generate a gene expression profile on the specific tumours and therefore possibly identify those responsible for overall tumour development.  
