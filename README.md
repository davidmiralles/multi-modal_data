# multi-modal_data

This repository contains the haptic and visual datasets used for the paper [Artificial visuo-haptic problem approach based on cross-modal internal representation].

## Haptic Dataset

The haptic dataset is divided in two directories, one for the baseline figures `haptic_dataset/BL` and the other for the unknown figures `haptic_dataset/UK`.

In each of these directories, there is a '.txt' file for each of the figures of the respective subset. Each of these files contains 21.000 haptic samples of the respective figure, where each sample is characterized as a three-position vector.

## Visual Dataset

The visual dataset is also divided in two directories, one for the baseline figures `visual_dataset/BL` and the other for the unknown figures `visual_dataset/UK`.

In each of these directories, there is a '.npy' file for each of the figures of the respective subset. Each of these files contains an array with 21.000 visual histograms of the respective figure, where each histogram represents an image of the figure and is constructed with 100 bins where 20 evenly spaced curvatures extracted from the image are represented.

## Authors: 
- Carlota Parés
- Guillem Garrofé
- Claudia Serrano
- Conrado Ruiz Jr.
- Alejandro González
- Raquel Ros
- David Miralles 