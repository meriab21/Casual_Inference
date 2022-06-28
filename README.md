# Casual_Inference

This project aims to extract useful features by using causal inferences and building the model to predict the diagnosis for breast cancer.


## Table of Content

- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Technologies used](#technologies-used)
- [Notebooks](#notebooks)
- [Scripts](#scripts)
- [Test](#test)

### Introduction
Breast-cancer Diagnostic being the second greates cause of death in cancer for women, it is considered most prevalent invasive cancer in females. Since 1989, significant progress has been made in the detection and treatment of breast cancer. More than 3.1 million Americans have survived breast cancer, according to the American Cancer Society (ACS). About 1 in 38 women will develop breast cancer in their lifetime (2.6 percent ). Early detection of the disease and precise diagnosis both increase the likelihood of long-term survival for a person with breast cancer.The prognosis, or anticipated long-term behavior of the disease, heavily influences the choice of appropriate therapy immediately following surgery.

The causal graph is a central object Judea Pearl framework but often unknown, subject to personal knowledge and bias, or loosely connected to the available data. In this project we will be highlighting the importance of the matter in a concrete way. we will be:

```
1. Perfoming a causal inference task using pearl's framework
1. Infer the causal graph from the observational data and then validate the graph
3. Merge machine learning with causal inference
```
### Data

- Data was found from kagle here https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?resource=download
- Features in the data are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

```
Attribute Information:
- ID number
- Diagnosis (M = malignant, B = benign)
- The remaining (3-32)

```

### Installation

```
git clone https://github.com/meriab21/Casual_Inference
cd Casual_Inference
pip install -r requirements.txt
```

### Technologies used

### Notebooks

All analysis and examples of implementation will be in juputer files will be found here.

### Scripts

All modules with different function for analysis are found here

### Test

All unit tests and integration will be found here
