# Speech-Sentiment-Analysis-

This project tackles the complex challenge of identifying emotions from voice recordings. Emotions are inherently subjective and typically inferred from visual cues like facial expressions and body language, making voice-based recognition a difficult task. Our goal is to create a model capable of effectively classifying the emotional tone in vocal expressions.

## Datasets
1. [RAVDESS](https://zenodo.org/record/1188976#.X2Q4Z2gzZPY)
2. [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)
3. [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/)
4. [CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D)
   


## Models

1. A CNN designed to analyze audio files' Mel Spectrograms.
2. A CNN focusing on Mel Frequency Cepstral Coefficients (MFCCs) of the audio files.
3. A CRNN that also works with MFCCs.
   


## Project Structure

1. Gathering Data
2. Data Organization and Cleaning
3. Data Exploration, Preparation, and Visualization
4. Data Preprocessing
5. Model Implementation 

All these components are detailed in the speech_emotion_recognition.ipynb Jupyter notebook.

## Insights
The Mel Spectrogram CNN was effective but struggled to differentiate some emotions. The CNN using MFCCs was the most successful, suggesting MFCCs are better for emotion recognition in audio. The CRNN with MFCCs also showed good results but was prone to overfitting and didn't surpass the MFCCs CNN.


## Evaluation Metrics
The models were assessed using Precision, Recall, and F1 scores, offering a more nuanced understanding of their effectiveness beyond mere accuracy. The MFCCs CNN model emerged as the top performer, as evidenced by its highest scores in these metrics.
