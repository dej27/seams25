# Experiment Validation with FiftyOne

This repository contains the data used for experiment validation. 
It includes machine learning model weights and trained ML model checkpoints for use with the FiftyOne platform.

## Repository Structure

- `MLMs` contain various pre-trained models used for RQ1 and RQ2 experiments (download from [here](https://www.dropbox.com/scl/fo/i97wsg7vptifazivt1dk2/AAMY4J5U4hm4msN8YlSwY6c?rlkey=emr4144h0ryd8pn0krubm66pq&st=qktd9qw4&dl=0))
- `yolo_evolve` contains re-trained model versions for every 10 epochs from RQ3 experiment (download from [here](https://www.dropbox.com/scl/fo/i97wsg7vptifazivt1dk2/AAMY4J5U4hm4msN8YlSwY6c?rlkey=emr4144h0ryd8pn0krubm66pq&st=qktd9qw4&dl=0)).
- $D_{stream}$ contains annotated data used for RQ3 with evolving MLC
- $D_{shadow}$ contains annotated data for all pre-trained MLMS ($v_{0...4}$)
- $D_{val}$ contains annotated data for all pre-trained MLMs ($v_{0...4}$)

Note: MLM model weights for $v_2$ and $v_4$ can be downloaded using [yolo-nas](https://docs.voxel51.com/user_guide/model_zoo/models.html#yolo-nas-torch) and [transformer](https://docs.voxel51.com/user_guide/model_zoo/models.html#detection-transformer-torch) links.
