# Prediction of standard cell types and functional markers from flow cytometry gating definitions using machine learning

This repository contain the notebook scripts and dataset used for prediction of cell types and functional markers.

#### Included files:

* *gating_definition_classification.ipynb*: main scripts

* *dataset.tsv*: dataset for training and test

The dataset includes the following data types:

Reportable name: input data
Marker: manually annotated functional marker
Laboratory: laboratory (or internal) creator of the flow cytometry assay
Cell Subtype: manually annotated cell type

It requires the PRO ontology to fully run ("pro_reasoned.owl").
