# Using Brain-Computer Interfaces for Emotion Detection with EEG Signal Processing and Classification

## Introduction

An electroencephalogram (EEG) is a recording of the brain activity measured by electrodes. EEG signals were first recorded in 1924 by Hans Berger, an incredible discovery that has lead to an area of research that is still being heavily researched today with a lot of unknowns. The collection of EEG signals is non-invasive and the electrodes are placed on the scalp with gel or paste. The most common use of EEG signals for medical reasons include Epilepsy research and sleep studies. They are also used to discover brain injuries, brain inflammation, and strokes.

## Objectives

Although EEG signals are routinely used for medical practice, this research is focused on if and how EEG signals could be used for more subjective approaches, such as human emotions and sentiment. By aligning the participant’s surveys about the music videos (subjective) as well as the EEG data (objective) we can begin to understand if it is possible to predict emotions from EEG signals. 

## The dataset

The dataset was created by Queen Mary University of London and can be accessed at https://www.eecs.qmul.ac.uk/mmv/datasets/deap/index.html. The dataset is open for public use and requires signing a release form; therefore the dataset cannot be accessed through this github repository.
The dataset consists of:

32 Participants
40 Channels (The first 32 channels are EEG)
40 One-minute videos
Labels: Valence, Arousal, Dominance, Liking, Familiarity, Order
EEG Channel Names- 'Fp1', 'AF3', 'F3', 'F7', 'FC5', 'FC1', 'C3', 'T7', 'CP5', 'CP1', 'P3', 'P7', 'PO3', 'O1', 'Oz', 'Pz','Fp2', 'AF4', 'Fz', 'F4', 'F8', 'FC6', 'FC2', 'Cz', 'C4', 'T8', 'CP6', 'CP2', 'P4', 'P8', 'PO4', 'O2'

## Methodology

This project will be following the data science O.S.E.M.N Methodology.

O — Obtaining the data
1.1 Import Data
1.2 Initial Data Exploration

S — Scrubbing & Cleaning the data
2.1 Marking Bad Channels
2.2 Filtering bandpass
  2.3 Detecting Artifacts
  2.4 Eliminating Artifacts

E — Exploring the data
  3.1 Finding Epochs
  3.2 Rejecting Epochs
  3.3 Creating DataFrame

M — Modeling the data
  4.1 K Nearest Neighbors
  4.2 K Nearest Neighbors - Using best K
  4.3 Decision Tree Classifier
  4.4 Bagged Tree
  4.5 Grid Search- Decision Tree Classifier
  4.6 Random Forest Classifier
  4.7 Grid Search- Random Forest Classifier

N — Interpreting the data
  5.1 Conclusions
  5.2 Moving Forward
