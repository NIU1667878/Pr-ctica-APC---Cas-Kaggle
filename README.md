# Practica_APC-Cas_Kaggle
## Pràtica final per l'assignatura de Aprenentatge Computacional del grau de MatCAD. 
Laia Querol Alturo

------------------
Mushroom identification is a popular activity among nature enthusiasts, hikers, and foragers who either intentionally search for mushrooms or encounter them by chance during outdoor excursions. For these individuals, being able to accurately identify mushrooms can be both a rewarding experience and an important safety measure, as some mushrooms are edible while others can be toxic. However, the task of distinguishing between different species and genera can be challenging due to the wide variety of mushrooms and the subtle differences in their appearance. This is where an automated identification system can prove to be quite helpful, providing a reliable and accessible way for individuals to classify mushrooms on the go using their smartphones or other devices.
    
In biological classification, genus is a taxonomic rank that groups together species that share common characteristics. It is one of the key levels in the hierarchical system of taxonomy, falling between family and species. A genus typically includes multiple species that are closely related but differ in certain morphological or genetic traits. For example, the genus Agaricus includes various species of mushrooms, such as Agaricus bisporus (commonly known as the button mushroom), and Agaricus arvensis (the horse mushroom). These well-known species exemplify the diversity within the genus Agaricus. Genus-level classification is an essential step in identifying and studying fungi, as it provides a broader categorization that can be useful for understanding their ecological roles, potential toxicity, and other biological properties.

We propose an approach that combines both local and global image features to improve the accuracy of mushroom classification. Our method integrates techniques such as the Bag of Visual Words (BoVW) and color histograms to create robust feature representations for mushroom images, which are then used for classification.

----------
## The Dataset
Given the size of the data, even zipped (111mb) -and split zipped- the data will have to be accessed through its original source at https://www.kaggle.com/datasets/mdhasanahmad/12-mushroom-species-dataset. 
I want to give special thanks to Hasan Ahmad for their work. The very first box of the notebook includes the lines that will have to be uncommented in order to download it. Once that is done, which should only take a couple of minutes, you will find inside Data, 12 folders of 1000 images each of size 224x224. Each folder is a genus of mushroom.

## Package Requirements
Python packages are the usual for a machine learning project. You should be mindfull of open-cv, sklearn and seaborn. 

## Execution
Setting variable 'full' to False will spare you from the full execution experience. I have set some executions under this boolean to avoid unnecessary experiments that just prolong execution time without providing much insight into the problem at hand. Nonetheless, the notebook as uploaded includes everything.

The notebook has the same structure as the report, making it easy to follow along. The very last cell includes the whole final pipeline with all optimizations. That is, reading the data, creating the features, treating them and using them in our favourite classifier. 

## Results
As our final accuracy we have obtained 83%, showing a drastic improvement from my very first execution at 18% and, of course, even greater than a random classifier which would sit at 8.33%. We can conlude our project to be of great use to beginner mushroom enthusiasts in search of classifiying the one and only mushroom they have found in their mushroom-searching endeavours in our very own dry forests. 


