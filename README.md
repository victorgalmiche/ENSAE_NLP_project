# ENSAE_NLP_project

Repository for the project of the course "Machine Learning for Natural Language Processing" at ENSAE. 

This project focuses on the study of manifestos of candidates in the elections of the French Vth republic, available through the Archelec corpus, collected by Sciences Po.

## Repository Structure

The text files are available in the `text_files` folder, ordered by year of the elections.
The `data` folder contains the metadata in CSV format and also a list of stopwords. 
The code is in notebooks in the `notebooks` folder: there is a notebook for the statistical study of the data, one for a preprocessing and the last one which focus on the core of this project, the conducting of topic modeling methods. 
The `figures` folder contains some figures extracted from the notebooks and useful for the report called `ENSAE_NLP_Project.pdf`. 

## Installation

To replicate the experiments, follow these steps:

**1. Clone the repository**
```bash
git clone https://github.com/victorgalmiche/ENSAE_NLP_project.git
cd ENSAE_NLP_project
```

**2. Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate       
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

## Usage 

Launch Jupyter and open the notebooks in the following order:

1. `notebooks/statistical_study.ipynb`: exploratory and statistical analysis of the corpus
2. `notebooks/preprocessing.ipynb`: text cleaning and preprocessing pipeline
3. `notebooks/topic_modeling.ipynb`: topic modeling experiments and results