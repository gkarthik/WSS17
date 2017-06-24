# Feature extraction from viral genomic sequences to enable Pathogen classification. 

Viruses have been classified into the taxonomy tree using by unifying molecular and morphological data. However, viruses within the same genus might vary greatly in their potential to infect human beings. A simple example us the [Flavivirus](https://en.wikipedia.org/wiki/Flavivirus#Species) genus which contains species such as Zika, Dengue, West Nile and Yellow Fever viruses all of which are pathogenic to humans. At the same time, the genus also contains species such as the Palm Creek virus that have been shown to be harmless in humans. 

The goal of the project is to train Convolutional Neural Networks to identify pathogenic viral species from genomic sequences. Viral genomic sequences will be extracted from the NCBI Reference Sequence Database([RefSeq](https://www.ncbi.nlm.nih.gov/refseq/)) and added to the Wolfram Data Repository. The pathogenic viral genomes will then be extracted using information from the [Human Disease Ontology](http://disease-ontology.org/). A Convolution Layer will be used to reduce the dimensionality of the viral genome prior to training the Neural Network. 


