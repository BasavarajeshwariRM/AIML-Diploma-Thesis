# Prediction and Classification of organisms using codon usage bias (CUB) frequencies

Every living organism, whether unicellular or multicellular, possesses a genome comprising nuclear DNA, mitochondrial DNA, and/or chloroplast DNA, all formed from nucleotide sequences (A, T/U, G, C). Codons, trinucleotide DNA sequences, correspond to specific amino acids, with 64 codons coding for 21 amino acids and a stop signal. Due to the genetic code's redundancy, a single amino acid can be encoded by one to five codons, leading to codon usage bias—a preference for specific codons coding for the same amino acid. This bias varies across taxa and offers insights into the taxonomic and phylogenetic features of organisms. 

Leveraging artificial intelligence and machine learning, we aim to determine if codon usage bias can predict and classify taxonomic identity and genetic composition across the kingdoms of life.

Various multiclass classification algorithms viz., (1) K-Nearest Neighbors (2) Decision tree (3) Random Forest (4) Gradient boosting (5) Gaussian Naive Bayes (6) Kernel SVM were employed in this study.

Among the algorithms, KNN performance was best in terms of Mathew’s correlation co-efficient metrics. Since the data points belonging to a particular kingdom were grouped into smaller sub-clusters, where KNN with 3 nearest neighbors had an advantage over the other models.  A test score of 0.939 was observed for the KNN model. The next best performing model was kernel SVM followed by gradient boosting with test score of 0.932 and 0.907 respectively. 
## Features

- Data Preprocessing
- Exploratory Data Analysis
- Modelling and Error Analysis
- Hyperparameter Tuning


## Dataset

The codon usage frequencies data has been extracted from the CUTG database which is constructed using the nucleotide sequences of 3,027,973 complete protein coding genes (CDS’s) of 35,779 organisms available in NCBI-GenBank. The individual files of CUTG database has been compiled into a joint database of 13028 genomes and is made available in the UCI Machine Learning Repository

https://archive.ics.uci.edu/ml/datasets/Codon+usage
## Acknowledgements

 - [Codon Usage Dataset](https://doi.org/10.1038/s41598-023-28965-7)
 


## Related Article

 - [Reading Material](https://www.researchgate.net/publication/346432520_Codon_Usage_Bias_Levels_Predict_Taxonomic_Identity_and_Genetic_Composition)
## Feedback

If you have any feedback, please reach out to us at rajeshwari.rm22@gmail.com

## License

[MIT](https://choosealicense.com/licenses/mit/)


