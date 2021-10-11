# Analyzing of EEG signals Using Deep neural networks
It is a Reasearch Project which aims to classifiy EEG signals after analyzing of dataset. 

objective: To Classify Active state and Inactive state of the signal using raw EEG dataset

Dataset:  16 subjects loaded: each subect correspond to 2 file: before arthmetic task(3 min) raw EEG signals and during arthmetic task raw EEG signals(1min)

Input: 21 features corresponding to 90k rows therefore final dataset size is 90k*21

output: labels 0, 1 active or inactive respectively

3 models were tested in this experiment:
   -1) LSTM MODEL
   -2) BIDIRECTIONAL LSTM 
   -3) LSTM WITH ATTENTION
   
