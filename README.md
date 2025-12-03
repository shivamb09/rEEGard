# rEEGard
This repo contains all the codes for EEG prediction. There are various python notebooks varying from simple random forest models to a deep learning based CNN + biLSTM model for this task.The datasets are Bern Barcelona EEG patients, GAMMEMO dataset and UCLA parkinson dataset that can be downloaded from the internet.

1) EDA_all_datasets contains the data analysis of the three datasets used.(The raw EEG signals have undergone signal processing and a set of 44 features have been extracted from them)

2) rEEGard_ver2 is a simple random forest model for this classification task. We have undegone hyperparameter tuning for BERN barcelona dataset and those parameters were used for the remaining two datasets.

3) rEEGard_NN is a simple multi-layer perceptron model using pytorch to see whether these features have that classification power.

4) rEEGard_DL consist of multiple models which were checked for better performance. Since the handpicked feartures were not performing well we took the raw EEG signal data and split it for various window size and checked a bi-LSTM model but then figured that the two data points overlap and dont have distinguishing power, so we used a CNN for feature extraction and then used a bi-LSTM for classification
