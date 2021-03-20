# Eye_tracking

This repo is submission from my team for the Eye tracking competition. The link to the competition organizers is:
https://cmclorg.github.io/

This repo provides the files to tag the data. Use the provided script. Analysis.py to generate the files with the BERT small embedding. Each of the words are treated as separate sentence for the process of extraction of embedding.

## CNN
Files CNN.py, traintf.py provides the details of the DL model I used to extract the emdeddings. It will train separate models for the each of the field. During the inference time. It will load each modules separately and prepare the inference output. 

For CNN, there is flag that will ensure what would be the context length for the processing.

## LGBM
The file Data Preparation LGBM.py provides the steps used for preparing the data and extracting features for training the model.

The file LGBM Regressor.py provides the details of the models finally applied to the data

Added the modules that was used to train on the colab. 
