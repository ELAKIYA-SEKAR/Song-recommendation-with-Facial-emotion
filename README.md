# Emotify

Emotify is a unique "Music Recommendation System” that seamlessly integrates emotion detection through facial recognition. The model used in this project achieves an accuracy of approximately 72% on the provided dataset.

The system adapts music recommendations from Spotify based on users’ emotions, identified from 7 distinctive moods:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

## Features

- **Facial Emotion Detection**: Utilizes OpenCV and Keras for real-time emotion detection through webcam input.
- **Integration with Spotify**: Seamlessly integrates with Spotify API to play songs based on detected emotions.
- **Frontend**: React app with a 'Try Emotify' button that initiates the emotion detection process.


## Training Your Own Model

If you want to train your own emotion recognition model using a different dataset or architecture, you can modify the `main.py` script and use the dataset of your choice. Be sure to update the `model.h5` file with your new model.
