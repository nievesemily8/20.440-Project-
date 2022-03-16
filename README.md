# 20.440-Project-

Overview 
--------
This repository contains a zipped file of miRNA and mRNA data from tumors of patients with breast cancer and the metadata to help access case data and link miRNA data with 
mRNA. Data_exploration is a python notebook that contains the code to generate a histogram of read counts from microRNA hsa-mir-98 from the patient data. 

Data 
---------
Data contains miRNA and mRNA expression data from patients with breast cancer (project TCA-BRCA) from the 
National Cancer Institutes Genomic Data Commons (https://portal.gdc.cancer.gov/.

Folder Structure 
-----------
Data folder contains the zipped file and metadata needed to sort through the cases and access data from inside the script. Scripts folder contains the code to reproduce the figure. 

Installation
------ 
The scripts require installation of seaborn, numpy, json, pandas, and matplotlib. The data folder containing patient data needs to be unzipped. 
Code was written in python 3.7.11
