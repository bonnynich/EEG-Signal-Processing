# Using Brain-Computer Interfaces for Emotion Detection with EEG Signal Processing and Classification

## Introduction

An electroencephalogram (EEG) is a recording of the brain activity measured by electrodes. EEG signals were first recorded in 1924 by Hans Berger, an incredible discovery that has lead to an area of research that is still being heavily researched today with a lot of unknowns. The collection of EEG signals is non-invasive and the electrodes are placed on the scalp with gel or paste. The most common use of EEG signals for medical reasons include Epilepsy research and sleep studies. They are also used to discover brain injuries, brain inflammation, and strokes.

## Objectives

Although EEG signals are routinely used for medical practice, this research is focused on if and how EEG signals could be used for more subjective approaches, such as human emotions and sentiment. By aligning the participant’s surveys about the music videos (subjective) as well as the EEG data (objective) we can begin to understand if it is possible to predict emotions from EEG signals. 

## The dataset

The dataset was created by Queen Mary University of London and can be accessed at https://www.eecs.qmul.ac.uk/mmv/datasets/deap/index.html. The dataset is open for public use and requires signing a release form; therefore the dataset cannot be accessed through this github repository.
The dataset consists of:

1. 32 Participants
2. 40 Channels (The first 32 channels are EEG)
3. 40 One-minute videos
4. Labels: Valence, Arousal, Dominance, Liking, Familiarity, Order
4. EEG Channel Names- 'Fp1', 'AF3', 'F3', 'F7', 'FC5', 'FC1', 'C3', 'T7', 'CP5', 'CP1', 'P3', 'P7', 'PO3', 'O1', 'Oz', 'Pz','Fp2', 'AF4', 'Fz', 'F4', 'F8', 'FC6', 'FC2', 'Cz', 'C4', 'T8', 'CP6', 'CP2', 'P4', 'P8', 'PO4', 'O2'

## Methodology

This project will be following the data science O.S.E.M.N Methodology.

O — Obtaining the data
- Import Data
- Initial Data Exploration

S — Scrubbing & Cleaning the data
- Marking Bad Channels
- Filtering bandpass
- Detecting Artifacts
- Eliminating Artifacts

E — Exploring the data
- Finding Epochs
- Rejecting Epochs
- Creating DataFrame

M — Modeling the data
- K Nearest Neighbors
- K Nearest Neighbors - Using best K
- Decision Tree Classifier
- Bagged Tree
- Grid Search- Decision Tree Classifier
- Random Forest Classifier
- Grid Search- Random Forest Classifier

N — Interpreting the data
- Conclusions
- Moving Forward
