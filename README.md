# VariabilityEuSN

This repository contains the TensorFlow 2.0 / Keras code for the experiments reported in the paper

Gallicchio, C. (2023). Diversifying Non-dissipative Reservoir Computing Dynamics. In: Iliadis, L., Papaleonidas, A., Angelov, P., Jayne, C. (eds) Artificial Neural Networks and Machine Learning – ICANN 2023. ICANN 2023. Lecture Notes in Computer Science, vol 14261. Springer, Cham. https://doi.org/10.1007/978-3-031-44198-1_15

## Files
Currently, two files are provided

* 'euler.py', which contains the main classes definition, including the EulerReservoirCell, the EuSN, and all the recurrent layers and architectures used in the experiments (including the variants tested in the paper, and the standard Echo State Network for comparison).
* 'experiments.py', which contains the code to run for the experiments on the time-series classificatiion tasks reported in the paper.

## Datasets

The pool of datasets used in the paper can be downloaded from the following link 
https://www.dropbox.com/scl/fo/0kbqezo00vye79sk3lvs5/h?rlkey=vqu0hkglqphj00s2nf4n692kv&dl=0
