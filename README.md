DeepHECT Dataset Repository

Overview

This repository contains the datasets used for training and testing the DeepHECT model, a hybrid deep learning framework for precise identification of HECT family E3 ligases from protein sequences.

Dataset Description

Three distinct datasets were constructed from animal proteomes. All HECT protein sequences were identified using HMMER against the Pfam HECT domain (PF00632) with an E-value threshold of 1e-10. Non-HECT sequences were randomly selected to create balanced datasets.

Each downloadable .zip file contains two FASTA format files:

HECT.fasta: Contains the HECT protein sequences (positive samples).

non-HECT.fasta: Contains the non-HECT protein sequences (negative samples).

1. Dataset 1 (dataset1.zip)

Description: The primary dataset for model training.

Files:

HECT.fasta

non-HECT.fasta

2. Dataset 2 (dataset2.zip)
   
Description: A smaller, focused dataset used for hyperparameter optimization, ablation studies, and comparative experiments with traditional ML models.

Files:

HECT.fasta

non-HECT.fasta

3. Independent Test Set (independent_test_set.zip)
   
Description: A held-out test set used for the final evaluation of the DeepHECT model and all comparative methods. All sequences are from goat breeds (Capra hircus), ensuring no taxonomic overlap with the training data.

Files:

HECT.fasta

non-HECT.fasta
