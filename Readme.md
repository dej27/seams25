# Experiment Validation with FiftyOne

This repository contains the data used for experiment validation. 
It includes machine learning model weights and trained ML model checkpoints for use with the FiftyOne platform.

## Repository Structure

- `MLMs` contain various pre-trained models used for RQ1 and RQ2 experiments
- `yolo_evolve` contains re-trained model versions for every 10 epochs from RQ3 experiment.
- $D_{stream}$ contains annotated data used for RQ3 with evolving MLC
- $D_{shadow}$ contains annotated data for all pre-trained MLMS ($v_{0...4}$)
- $D_{val}$ contains annotated data for all pre-trained MLMs ($v_{0...4}$)