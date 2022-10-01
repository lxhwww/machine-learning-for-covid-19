# machine-learning-for-covid-19


## Background: 
With the global spread of COVID-19, the world has seen many patients, including many severe cases. The rapid development of machine learning (ML) has made significant disease diagnosis and prediction achievements. Current studies have confirmed that omics data at the host level can reflect the development process and prognosis of the disease. Since early diagnosis and effective treatment of severe COVID-19 patients remains challenging, this research aims to use omics data in different ML models for COVID-19 diagnosis and prognosis. We used several ML models on omics data of a large number of individuals to first predict whether patients are COVID-19 positive or negative, followed by the severity of the disease. 

## Results: 
On the COVID-19 diagnosis task with single omic data, we got the best AUC of 0.99 with a multilayer perceptron model and the highest F1-score of 0.95 with a logistic regression (LR) model. For the severity prediction task, we achieved the highest accuracy of 0.76 with an LR model. 

## Conclusions: 
This study diagnoses COVID-19 positive cases and predicts accurate severity levels. It lowers the dependence on clinical data and professional judgment, which is conducive to triaging patients of different severity levels. Hospital and public health care mechanisms can optimise the distribution of medical resources and improve the robustness of the medical system.

## File Description:
### EX1:Detection and Prognosis of Covid-19 Patients with Single-Omic Data
####data:
DNA-methylation data:
RNA-seq data:
The proteomics and metabolomics data:
In this section, we first investigate the performance of models using single-omics data with only simple preprocessing and feature transformations, and without fusion of multiple omics data. We implement the detection of covid-19 negatives and positives, and the prediction of severity, on separate datasets. We used several single omic data to build machine learning and neural network models for the detection of covid-19 negatives and positives.

### EX2:
DNA-methylation data:
RNA-seq data:
The proteomics and metabolomics data:
The four-omic data Mass spectrometry raw files and the SQLite database file have been deposited to the MassIVE database (accession number MSV000085703; \url{https://doi.org/10.25345/C5F74G}). We use the data based on \textit{Large-Scale Multi-omic Analysis of COVID-19 Severity}.\citep{overmyer2021large}

### Data:  
