OFF-TARGET PREDICTIONS IN CRISPR-CAS9 GENE EDITING BASED ON MATCH SCORE USING MACHINE LEARNING

This repository includes machine learning tools for predicting the off-targets in CRISPR-Cas9 gene editing [1] 

RAW DATASET

The classifiers were trained and tested on datasets that cleaned and encoded from the result dataset of the previous experiment conducted using deep learning techniques.
This folder also contains the cleaned dataset which will be further encoded for classification.

INSERTION & DELETION

The code files for encoding the raw dataset, training the encoded dataset and testing the encoding dataset are present in this folder to classify the “Insertion” and “Deletion” of nucleotides.
This folder also contains the encoded dataset obtained by cleaned dataset and the result dataset obtained from test set.

MATCH & MISMATCH

The code files for encoding the raw dataset, training the encoded dataset and testing the encoding dataset are present in this folder.to classify the “on-targets” (Match) and “off-targets” (Mismatch) of the nucleotide sequences.
This folder also contains the encoded dataset obtained by cleaned dataset and the result dataset obtained from test set.

SUPPLEMENTARY MATERIALS

The graphs and tables of the results are added in this folder.
This folder also contains the image representation of the classifiers used in this study and how the match score is calculated between the nucleotide sequences.

PREREQUISITES

The models for off-target predictions based on match score were conducted by using python3.6 available on google colabs. Following packages should be installed
•	Lightgbm
•	Matplotlib.pyplot
•	Numpy
•	Sklearn

REFERENCES

1.	Lin J, Wong KC. Off-target predictions in CRISPR-Cas9 gene editing using deep learning. Bioinformatics. 2018;34(17):i656-i663. doi:10.1093/bioinformatics/bty554. [PubMed]

Prasoon Kumar - 
Prasoonk02@gmail.com - 
July 04 2020
