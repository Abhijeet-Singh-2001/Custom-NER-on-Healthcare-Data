# Custom-NER-on-Healthcare-Data
Description / Summary:
This project implements a Custom Named Entity Recognition (NER) system on medical text to identify diseases and treatments. Using CRF (Conditional Random Fields) and spaCy, the model extracts entities from sentences and builds a disease-treatment mapping for healthcare analytics.
This project implements a Custom Named Entity Recognition (NER) system on medical text to identify diseases and treatments. Using CRF (Conditional Random Fields) and spaCy, the model extracts entities from sentences and builds a disease-treatment mapping for healthcare analytics.

Objectives:
Build a custom NER system to identify medical entities.
Extract diseases and their corresponding treatments from medical text.
Evaluate the CRF model using F1-score metrics.
Dataset: Custom annotated medical dataset (train/test CSVs)
**Tech Stack: **Python, spaCy, sklearn-crfsuite, pandas

Key Insights:
Contextual PoS tagging significantly improves entity recognition.
Achieved an F1-score of ~91% on the test set.
Successfully mapped diseases to potential treatments from unstructured text.
