# rEEGard
This repo contains all the codes for EEG prediction. There are various python notebooks varying from simple random forest models to a deep learning based CNN + biLSTM model for this task.The datasets are Bern Barcelona EEG patients, GAMMEMO dataset and UCLA parkinson dataset that can be downloaded from the internet.
EDA_all_datasets contains the data analysis of the three datasets used.(The raw EEG signals have undergone signal processing and a set of 44 features have been extracted from them)
rEEGard_ver2 is a simple random forest model for this classification task. We have undegone hyperparameter tuning for BERN barcelona dataset and those parameters were used for the remaining two datasets.
