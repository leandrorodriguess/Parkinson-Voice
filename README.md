# Python-code for Diagnosing Parkinson's Disease through Patient Voice Analysis using Machine Learning Models.

## Abstract

Parkinson's Disease (PD) is a neurological disorder affecting millions worldwide, with vocal disturbances evident in approximately 90% of patients in the early stages. Machine Learning (ML) offers promising tools to aid in the diagnosis of PD by analyzing voice recordings. In this article, we present Python codes that facilitate the application of various ML algorithms to classify patients with PD based on voice recordings. These codes provide an accessible means for researchers to implement Logistic Regression, Random Forest, Support Vector Machines, k-Nearest Neighbors, and Naïve Bayes classifiers, demonstrating their efficacy in distinguishing between healthy individuals and PD patients.

The Python scripts were developed using public voice data from the UCI Machine Learning Repository [3], originally collected by Naranjo et al. [2]. Preprocessing techniques such as logarithmic scaling and min-max normalization were employed to prepare the dataset. The codes include detailed implementations for training and testing the ML models, along with performance metrics such as accuracy, precision, recall, F1-score, and ROC curves.

The results obtained using these Python codes were published in the proceedings of the XIV Simpósio de Engenharia Biomédica (ISSN: 2358-3568) [1]. This study demonstrated the effectiveness of ML models in identifying PD from voice recordings, providing a valuable resource for further research and clinical applications.

A key feature of our implementation is the use of cross-validation to ensure robust model evaluation. The Naïve Bayes classifier, in particular, exhibited the highest accuracy among the tested models, highlighting its potential for early PD diagnosis. By providing these Python codes, we aim to support future research in developing reliable diagnostic tools and contribute to the broader field of medical data science.

These codes offer a comprehensive toolkit for ML-based voice analysis, empowering researchers and clinicians to harness the power of ML for early and accurate diagnosis of PD. The provided scripts include functions for data preprocessing, model training, and evaluation, ensuring reproducibility and ease of use in various experimental setups.

## Reference

[1] D. H. da. Silva, C. T. Ribeiroe A. A. Pereira, “Um estudo sobre o uso de modelos de Machine Learning para o diagnóstico da Doença de Parkinson por meio da análise de voz de pacientes”, dez. 2022. https://doi.org/10.5281/zenodo.7490097

[2] L. Naranjo, C. J. Pérez, Y. Campos-Roca, and J. Martín, “Addressing voice recording replications for Parkinson’s disease detection,” Expert Syst Appl, vol. 46, pp. 286–292, Mar. 2016. https://doi.org/10.1016/j.eswa.2015.10.034

[3] Prez, Carlos. (2019). Parkinson Dataset with replicated acoustic features. UCI Machine Learning Repository. https://doi.org/10.24432/C5701F
