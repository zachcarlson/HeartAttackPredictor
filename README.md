
# Predicting Heart Attack Risk Using Machine Learning Techniques

## Project Overview

This repository was created for the DSCI 631 course at Drexel University, Applied Machine Learning. The overall scope of this project was to predict heart attack risk using Machine Learning techniques based off other health- and heart-based parameters.  The heart attack database was downloaded from [Kaggle](https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset).

## File Manifest: 

- `HeartAttackPredictor.ipynb` - Main code that predicts heart attack risk using Machine Learning techniques.
- `Folder /data` - Contains all data files 
  - `heart.csv` - Heart Attack data (source in **Project Overview**)
- `Folder /documents` - Contains all miscellaneous documents
  - `Project Proposal.docx` - Project proposal word document, required for class
  - `DSCI 631 Final Project Presentation` - PowerPoint presentation slides of project
  - `presentation_background.jpg` - Background image used on first slide of presentation
- `Folder /.ipynb_checkpoints` - Contains checkpoint saves of `HeartAttackPredictor.ipynb`.
- `Folder /images` - Contains all images downloaded from Notebook.

## Reason for Project:
There are several factors that doctors must consider quickly when assessing a patient's risk for heart attack.  These include: age, sex, chest pain type, resting blood pressure, cholesterol and more.  Creating a machine learning algorithm to detect patterns and more accurately predict risk will save lives and save time for doctors to focus on other patients.

## Team Members

Our team consisted of the following individuals: 

- Zach Carlson, zc378@drexel.edu
- Andrew Napolitano, asn65@drexel.edu
- Tyler Bread, tb3245@drexel.edu

## Requirements
- Python ≥ 3.8. 
- Python modules, packages, and methods required: 
    - `pandas`
    - `matplotlib.pylot`
    - `numpy`
    - `seaborn`
    - `sklearn`
    - `warnings`
    - `xgboost`

## How to Execute Code: 

All of the code in this project needs to be opened with the Jupyter notebook environment. We recommend using [Anaconda](https://www.anaconda.com/products/individual) to help with Jupyter notebook.  Additionally, this code can be run in Google Colab or your preferred Python coding environment, assuming folder organization remains unchanged.

**Ensure to change `

## Known Limitations of Project:

- **This Machine Learning (ML) pipeline does not address ANNs**, as it was not in-scope for the project and there was not time to implement.  
- **The dataset is only ~300 instances.**  For this to be practical and a valid tool for assessing real patient risk, there would need to be a significantly large number of instances to train the ML pipeline with.
- While this is a very popular dataset on Kaggle, and served as a great training dataset in a class setting, **there was no source or explanation on where the data came from.**  It could have been randomly generated or from a single hospital.  Fortunately, this was constructed in a classroom setting for educational purposes and not for any real-world healthcare applications.  Going forward, assessing the source of datasets before conducting projects or building ML pipelines will be critical.
