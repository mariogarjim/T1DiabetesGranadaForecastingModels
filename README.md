# *dIAbetes: Analyzing Diabetes Mellitus Data Using Artificial Intelligence Techniques*

This repository contains the code associated with the thesis _dIAbetes: Analyzing diabetes mellitus data using artificial intelligence techniques._ The objective of this thesis was to develop a model capable of predicting blood glucose levels in patients with type 1 diabetes (T1D), utilizing data from real patients. This project was conducted in collaboration with San Cecilio Clinic Hospital, Granada (Spain).

The dataset used in this project is the **T1DiabetesGranada** dataset [[1]](#1). The dataset consists in four years of glucose data from 736 T1D patients from the province of Granada in Spain

## Repository Structure

The codebase is organized into six jupiter notebooks:

1. **Autocorrelation**: Analyzes the autocorrelation of blood glucose (BG) measurements to understand temporal patterns.
2. **Interpolation_experiment**: Explores interpolation techniques to simulate and manage missing data.
3. **Measurements_distribution**: Examines the distribution of BG measurements to provide insights into data variability.
4. **Outliers**: Identifies and handles potential outliers in the BG dataset.
5. **Preprocessing**: Implements preprocessing techniques, producing a resampled dataset for subsequent model training in the _Models_ notebook.
6. **Models**: The main notebook, which executes the three core experiments of the thesis. Before using this notebook, ensure that the dataset is preprocessed by running _Preprocessing.ipynb_ before using this notebook.

<a id="1"></a>
### Reference
[1] Rodriguez-Leon, C., Aviles-Perez, M., Banos, O., Charneco, M., Lozano, P., Villalonga, C., & Muñoz-Torres, M. (2023). **T1DiabetesGranada: A longitudinal multi-modal dataset of type 1 diabetes mellitus**. *Scientific Data*, 10, p. 916. [https://doi.org/10.1038/s41597-023-02737-4](https://doi.org/10.1038/s41597-023-02737-4).
