<br/>**PSB 2025 Accepted Paper**<br/> 
<br/>**Diagnostic Code Definitions and Maps**<br/> 
1.) **ADRD_List_ICD9andICD10codes.csv** This file contains a list of ICD-10 and mapped ICD-9 codes for identifying Alzheimer's Disease and Related Dementias (ADRD) from Electronic Health Records (EHR) data.

2.) **ADRD_ICD10_Code_to_ICD9_Map.csv** This file contains the list of ICD-10 codes used to identify ADRD and their mapped ICD-9 codes using the following resource to map ICD-10 codes to ICD-9 codes utilized in July 2024: https://icd.codes/convert/icd10-to-icd9-cm

3.) **feature_penetrance_acrossmethods_and_subtypes_withoutNeuralNet_wphecode.csv** This file contains the list of features (PheCodes) used in this project and the number of methods that found that particular feature to be important across methods and Neural Degenerative Disorder (NDD) type. In this set, the NeuralNetwork results are **not** included and so there are 3 methods and 3 subtypes (AD, PD, and Dementias) indicating that 9 is the maximum number that a feature can have. A score of 9 indicates that the feature was determined to be important across all 3 methods (univariate logistic regression, multivariate logistic regression, multivariate ridge regression, and each of the subtypes AD, PD and Dementias).

4.) **feature_penetrance_acrossmethods_and_subtypes_wNeuralNet_NEW_wphecode.csv** This file contains the list of features (PheCodes) used in this project and the number of methods that found that particular feature to be important across methods and Neural Degenerative Disorder (NDD) type. In this set, the NeuralNetwork results are included and so there are 4 methods and 3 subtypes (AD, PD, and Dementias) indicating that 12 is the maximum number that a feature can have. A 12 indicates that the feature was determined to be important across all 4 methods (univariate logistic regression, multivariate logistic regression, multivariate ridge regression, neural network, and each of the subtypes AD, PD and Dementias). The difference between this file and the prior file is the inclusion of Neural Network results.


<br/>**Paper Under Review**<br/> 
1.) **fall_phecodes.csv** This file contains phecodes for identifying falls or injuries from Electronic Health Records (EHR) data. 


