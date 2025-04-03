# Electron-Photon-Classification-Common-Task-1

This repository follows the task guidelines by ML4SCI for the Common Task (Electron/Photon Classification) for GSOC 2025.

Goal: Design a ResNet-15 model for classification.

Dataset: 
https://cernbox.cern.ch/index.php/s/AtBT8y4MiQYFcgc (photons)
https://cernbox.cern.ch/index.php/s/FbXw3V4XNyYB3oA (electrons)

The datasets consists of 32x32 matrices with two channels: Hit energy, and Time for two types of particles, electorns and photons, hitting the detector.

We need to split the dataset into 80%-20% for training set and testing set respectively.

The architecture of the model used is described in the image below:

(add image)

