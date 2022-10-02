# Tissue_prediction_manuscript

This github repository contains code used in the manuscript on tissue prediction. 

The datasets and database can be found and downloaded from Zenodo:

## Abstract
"Using data from 183 public human data sets from PRIDE, a machine learning model was trained to identify tissue and cell-type specific protein patterns. PRIDE projects were searched with ionbot and tissue/cell type annotation was manually added. Data from physiological samples were used to train a Random Forest model on protein abundances to classify samples into tissues and cell types. Subsequently, a one-vs-all classification and feature importance were used to analyse the most discriminating protein abundances per class. Based on protein abundance alone, the model was able to predict tissues with 98% accuracy, and cell types with 99% accuracy. The F-scores describe a clear view on tissue-specific proteins and tissue-specific protein expression patterns. In-depth feature analysis shows slight confusion between physiologically similar tissues, demonstrating the capacity of the algorithm to detect biologically relevant patterns. These results can in turn inform downstream uses, from identification of the tissue of origin of proteins in complex samples such as liquid biopsies, to studying the proteome of tissue-like samples such as organoids and cell lines. "

## Notebooks
Model training notebooks

These notebooks contain code used to train multiple classifiers on the filtered and complete datasets:
* Tissue_predictors_filtered
* Tissue_predictors_full
* Cell_type_predictors_filtered
* Cell_type_predictors_full
 
## License
All data and downstream results of this research follow CC-BY-NC-4.0.
