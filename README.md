# Audio_Genre_Classification
This project used two deep learning methods to classify music on the basis of their genre. First method was used to convert the audio files into spectrograms and perform Transfer learning to classify the audio files. The second method extracted the MFCC features and perform CNN to classify the audio files.


##################################################################################################

1. The data set can be dowloaded from https://os.unil.cloud.switch.ch/fma/fma_small.zip
2. Download the file and unzip at the current working directory.
3. The files are to be run in the below order - 
    1. Feature_Extraction.ipynb
    2. Transfer_Learning.ipynb
    3. CNN_Model.ipynb
4. The metadata of the audio files are stored with the name 'metadata.csv'.
5. The hyperparameter tuning logs of HParam Dashboard already reside in logs/hparam_tuning.
6. Running the Transfer_Learning.ipynb notebook would replace the logs inside 'logs/hparam_tuning'

###################################################################################################
#### Thanks!
