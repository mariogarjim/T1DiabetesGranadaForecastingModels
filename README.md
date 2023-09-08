Author: Mario García Jiménez 

# TFG

This repo contains the associated code of the thesis dIAbetes: Analysing diabetes mellitus data using artificial intelligence techniques.
The objective of this thesis is to develop a Machine Learning model that allows predictions about blood glucose levels in patients with type 1 diabetes using data from real patients.

All this code has been performed using the T1DiabetesGranada. 

The code consists of 6 Google Collab notebooks. The nootbooks must be runned using Google Collab because they are connected to drive:

* Autocorrelation: Exploration of the autocorrelation of the blood glucose (BG) measurements.
* Interporaltion_experiment: Exploration of the interprolation technique for simulating missing data.
* Measurements_distribution: Exploration of the distribution of the BG measurements.
* Outliers: Search for outliers.
* Preprocessing: Preprocessing techniques. It generates the resampling dataset that is used in the Models notebook.
* Models: Main file of the repository. It creates the three different experiments of the thesis. Before running this file, the dataset must be preprocessed running Preprocessing.ipynb.

More info in the TFGMemoria-GarciaJimenezMario.pdf

