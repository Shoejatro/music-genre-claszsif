# music-genre-claszsif
audio-to-mfcc -> it basically converts waveform of each audio file into its MFCC vector and stores it in a JSON file.
mgrCNN -> we apply CNN to our preprocessed JSON file containing the MFCCs.
model_testing -> we load our model and try to predict the genre of some songs.

Link to the dataset:
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification?resource=download
