# Simple MIDI Generator
2 neural networks based on LSTM

The main idea of this project was to compare two neural networks with similar architecture, but different training dataset.
First NN was trained to generate midi files in Amin key only.
Second NN was trained to generate midi files in Amin and A#min keys.

Both NN were trained to generate melodies in 128 BPM and in the most generic EDM rhythm.

# Files Description
'NN_1.ipynb' - Jupyter notebook where i prepared midi data for training the 1st neural network, then created, trained and tested the 1st neural network based on LSTM. I saved the best weights for this model.

'NN_2.ipynb' - Jupyter notebook where i prepared midi data for training the 2nd neural network, then created, trained and tested the 2nd neural network based on LSTM. I saved the best weights for this model.

'model_1_weights.hdf5' - the best saved weights for the 1st NN.

'model_2_weights.hdf5' - the best saved weights for the 2nd NN.

'NN_1_and_2_final.ipynb' - Jupyter notebook with final midi generator, where both neural networks are created, but their weights are loaded from 'model_1_weights.hdf5' and 'model_2_weights.hdf5'. This generator makes 2 midi files ('Output_1.mid' and 'Output_2.mid').

'Dataset' (folder) - this folder contains 34 midi files with melodies from different progressive house tracks. There are melodies from Alex Aspen, Severman and Martin Garrix tracks and much more.
# Result of comparison
The first neural network generates much more pleasant melodies then the second neural network.
