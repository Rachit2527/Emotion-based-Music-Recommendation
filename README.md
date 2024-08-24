# Facial Emotion Music Player

## Overview
The Facial Emotion Music Player is an innovative music recommendation system that takes into account the user's facial emotions, preferred language, and favorite singer to curate a personalized playlist on YouTube. By leveraging deep learning techniques, the model detects the user's facial emotions in real-time and suggests music that matches their mood.

## Features
- **Emotion-Based Music Recommendation**: Detects six different emotions—happy, sad, surprised, angry, neutral, and party—to suggest songs that resonate with your current mood.
- **Language & Singer Preferences**: Allows users to specify their preferred language and singer to further refine the music recommendations.
- **Real-Time Emotion Detection**: Utilizes Mediapipe's facial and hand landmarks to capture and analyze facial expressions in real-time.
- **Streamlit Deployment**: The model is deployed on Streamlit, offering an intuitive and interactive user interface.
- **Seamless YouTube Integration**: Once the emotion is detected and preferences are set, the player opens a corresponding playlist or song directly on YouTube.

  ## How It Works

1. **Input**: The user provides their preferred language, favorite singer, and displays their current emotion through facial expressions.
2. **Emotion Detection**: The model, trained on a dataset collected using Mediapipe's facial and hand landmarks, identifies the user's emotion.
3. **Music Recommendation**: Based on the detected emotion, the model suggests songs that align with the user's mood, opening the selection on YouTube.

