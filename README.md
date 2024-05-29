# Audio_Sentimental_Analysis
Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human 
emotion and the associated effective states from speech. This is capitalizing on the fact that voice 
often reflects underlying emotion through tone and pitch. Emotion recognition is a rapidly growing 
research domain in recent years. Unlike humans, machines lack the abilities to perceive and show 
emotions. But human-computer interaction can be improved by implementing automated emotion 
recognition, thereby reducing the need for human intervention. In this project, basic emotions like 
calm, happy, fearful, disgust etc. are analysed from emotional speech signals. 
We have used RAVDESS dataset which contains around 1440 audio file inputs from 24 different 
actors (12 male and 12 female ),First, we analysed our dataset by plotting the spectrogram and 
waveforms of a sample audio file from the dataset. Then we extracted the features of the data using 
Mel Frequency Cepstral Coefficients (MFCCs), chroma frequencies, MeI spectrogram and Spectral 
centroid. Then we built a Multi-layer perceptron (MLP) model to predict the emotions of the audio 
data as well as the gender of the speaker. 
