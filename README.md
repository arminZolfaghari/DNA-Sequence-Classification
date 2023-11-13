# DNA-Sequence-Classification
Analysis of DNA Sequence Classification Using Neural Networks.
This project is the implementation of this [research article](https://pubmed.ncbi.nlm.nih.gov/34306171/).

In a general computational context for biomedical data analysis, DNA sequence classification is a crucial challenge. Several machine learning techniques have used to complete this task in recent years successfully. Identification and classification of viruses are essential to avoid an outbreak like COVID-19. Regardless, the feature selection process remains the most challenging aspect of the issue. The most commonly used representations worsen the case of high dimensionality, and sequences lack explicit features. It also helps in detecting the effect of viruses and drug design. In recent days, deep learning (DL) models can automatically extract the features from the input. In this work, we employed MLP using Label and K-mer encoding for DNA sequence classification.

In this project (Bioinformatics Course Project), we will classify 6 viruses with MLP. The genome of each virus is shown by nucleotide sequences that have different lengths. Adenine (A), cytosine (C), guanine (G), and thymine (T) are the four nucleotides that makeup DNA. The DNA of each virus is unique, and the pattern of arrangement of the nucleotides determines the unique characteristics of a virus.

First, the ```K-mer``` method was used to reduce the length of the DNA sequence, and then the ```Word to Vector``` method was used to convert it to a fixed length.

## Dataset
The [training set](https://github.com/arminZolfaghari/DNA-Sequence-Classification/blob/main/Dataset/training_set.csv) includes 1320  data that has 220 data for each virus.<br>
The [development set](https://github.com/arminZolfaghari/DNA-Sequence-Classification/blob/main/Dataset/development_set.csv) includes 30 data to check the model and evaluation.<br>
The [test set](https://github.com/arminZolfaghari/DNA-Sequence-Classification/blob/main/Dataset/test_set.csv) includes 400 data without a label, and we must predict the label (virus class).
