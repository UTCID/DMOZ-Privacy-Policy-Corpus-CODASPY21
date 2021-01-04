# DMOZ-Privacy-Policy-Corpus-CODASPY21
The privacy policy corpus of the CODASPY 21 dataset paper "A Large Publicly Available Corpus of Website Privacy Policies Based on DMOZ"

This ReadMe file explains the structure of the privacy policy corpus.

There are 15 folders, each including the privacy policies of one DMOZ category.
These categories of DMOZ, sorted alphabetically, are: 
(1) adult, 
(2) arts, 
(3) business, 
(4) computers, 
(5) games, 
(6) health, 
(7) home, 
(8) kids, 
(9) news, 
(10) recreation, 
(11) reference,
(12) science, 
(13) shopping, 
(14) society, 
(15) sports.

Each category, named cati-name where i is the category number, includes a set of text files.
Each text file, named domainURL-j, is the privacy policy of one unique privacy policy URL. Note that since the privacy practices of a website are often scattered across multiple pages, sometimes there are more than one text file for each domain URL. In these cases the counter j separates the files from one another.
The URL used in the file names is a variant of the actual URL in which all dots (.) are replaced with dashes (-) to avoid naming problems under different operating systems. If the use of this dataset needs the actual URL, he/she may safely retrieve the URL from the first line of the dataset.
The first line of each text file is the URL of the privacy policy.
The rest of the text file is the privacy policy text.

The dataset is made available for research, teaching, and scholarship purposes only, with further parameters in the spirit of a Creative Commons Attribution-NonCommercial License.

If you use this dataset as part of a publication, you must cite the following paper:
Zaeem, R. N., & Barber, K. S. A Large Publicly Available Corpus of Website Privacy Policies Based on DMOZ. In the 11th ACM Conference on Data and Application Security and Privacy (CODASPY 2021).

For more details about the database please see the paper and contact the authors: razieh@identity.utexas.edu and nokhbeh@gmail.com
