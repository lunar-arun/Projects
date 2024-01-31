# Named Entity Recognition (NER) Model

## Overview

This repository contains a Named Entity Recognition (NER) model built for identifying and classifying entities in text. NER is a subtask of information extraction that seeks to locate and classify named entities (persons, organizations, locations, etc.) in unstructured text.

## Model Architecture

The NER model is built using [choose your framework/library, e.g., SpaCy, NLTK, TensorFlow, PyTorch]. It leverages a LSTM, Bidirectional for sequence labeling.

## Dataset

The model was trained on the [Entity Annotated Corpus dataset](https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus?select=ner_dataset.csv) available on Kaggle. The dataset contains annotated examples of text with labeled entities.

To use this dataset:

1. Download the dataset from the Kaggle link.
2. Place the `ner_dataset.csv` file in the `data/` directory.
