# This is the repository for our AML project - Multimodal Emotion recognition of Audio signals. 

- Experiments
    - CNNExcludingIntensity.ipynb - Excludes intensity from the label. All intesnities greater than 0 are considered 1.
    - CNNImplementation.ipynb - Excludes intensity from the label. All intesnities greater than 0.334 are considered 1. Final blueprint for CNN model.
    - CNNLSTMTuning.ipynb - Explores tuning the models hyperparameters
    - LSTMImplementation.ipynb - Excludes intensity from the label. All intesnities greater than 0.334 are considered 1. Some feature processing explored. Final blueprint for LSTM model.
    - MFCCResampling

- MFCCs and data analysis
    - audioDataAnalysis.ipynb - Intitial data exploration and analysis.
    - audioDataProcessing.ipynb -  Uses CMU-MOSEI SDK to retrieve data alignments for preprocessing. Processes the raw text transcriptions and audio files and outputs aligned array files containing MFCCs, raw text, and labels for each example in the test, training, and dev sets.

- CNN_LSTM_MainNotebook.ipynb - Contains final results for the CNN, LSTM, and combined models.
- audioprojenv.yml - config file for environment.