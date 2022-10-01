# machine-learning-for-covid-19


## Background: 
With the global spread of COVID-19, the world has seen many patients, including many severe cases. The rapid development of machine learning (ML) has made significant disease diagnosis and prediction achievements. Current studies have confirmed that omics data at the host level can reflect the development process and prognosis of the disease. Since early diagnosis and effective treatment of severe COVID-19 patients remains challenging, this research aims to use omics data in different ML models for COVID-19 diagnosis and prognosis. We used several ML models on omics data of a large number of individuals to first predict whether patients are COVID-19 positive or negative, followed by the severity of the disease. 

## Results: 
On the COVID-19 diagnosis task with single omic data, we got the best AUC of 0.99 with a multilayer perceptron model and the highest F1-score of 0.95 with a logistic regression (LR) model. For the severity prediction task, we achieved the highest accuracy of 0.76 with an LR model. 

## Conclusions: 
This study diagnoses COVID-19 positive cases and predicts accurate severity levels. It lowers the dependence on clinical data and professional judgment, which is conducive to triaging patients of different severity levels. Hospital and public health care mechanisms can optimise the distribution of medical resources and improve the robustness of the medical system.

## File Description:
### EX1:Detection and Prognosis of Covid-19 Patients with Single-Omic Data
#### Data:
DNA-methylation data:   
available with the GSE174818 on GEO,with the link of https:  
www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE174818  
https://drive.google.com/file/d/16tuoof17zkJJqCXyxmzERLsr0Rg2lnjf/view?usp=sharing  
RNA-seq data: Data/ex1/RNA.csv  
The proteomics and metabolomics data: Data/ex1/Prot_and_meta_matrix.csv,Data/ex1/Prot_and_meta_matrix_C2.csv   
#### Experient:
In this section, we first investigate the performance of models using single-omics data with only simple preprocessing and feature transformations, and without fusion of multiple omics data. We implement the detection of covid-19 negatives and positives, and the prediction of severity, on separate datasets. We used several single omic data to build machine learning and neural network models for the detection of covid-19 negatives and positives.

### EX2:Prediction of Severity of Covid-19 Patients by Multi-Omic Data
#### Data:  
The four-omic data Mass spectrometry raw files and the SQLite database file have been deposited to the MassIVE database (accession number MSV000085703; https://doi.org/10.25345/C5F74G). We use the data based on Large-Scale Multi-omic Analysis of COVID-19 Severity.  
In our repostory:
#### Experient:
For the covid-19 severity prediction scenario, we show the effects of the classification model and the variability between subgroups, based on the experimental process,in the directions of training the classifier to obtain subgroups and validating the robustness. We compared and discussed the effects of different experimental approaches and the impact of different combinations of parameters and input data on the model performance. Validation results of the robustness of the classification results on an independent dataset are presented.


