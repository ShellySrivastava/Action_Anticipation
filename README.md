# Action_Anticipation
This repo contains the code for my MSc research work based on Action Anticipation using Acticipate Dataset.
The dataset can be downloaded from http://vislab.isr.ist.utl.pt/datasets/

* Platform: Google Colab
* Language: Python
* DL framework: Pytorch

* Additional packages used:
* OpenPose
* OpenCV

1. The original dataset can be downloaded from the link given above. The preprocessed files can be found in \Processed Dataset folder
2. The code for preprocessing and models can be found under \code
    * The folder contains interactive python notebooks with their outputs.
    * Check the file Preprocessing_Acticipate for preprocessing algorithms used.
    * Check the file LSTM_Anticipation for the base LSTM model and its implementation.
    * Check the file CNN_Anticipation for the implementation of the proposed CNN model.
3. The trained models used for reporting accuracy and performance can be found under \Trained Models
4. The numpy for accuracy per observation ratio can be found at \Accuracy info
5. The figures used in the report can be found at \Figures
