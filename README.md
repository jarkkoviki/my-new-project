# my-new-project
Building Ai course project

# MoodMusic AI

Final project for the Building AI course

## Summary

MoodMusic AI is an application that recommends music based on the user's mood. The system analyzes text, facial expression, or a selected emotional state and suggests a suitable playlist. The goal is to support emotional well-being and help regulate mood through music.

## Background

People often choose music based on how they feel — but finding the right music can take time. Music has been shown to influence emotional states, stress levels, and concentration. This project aims to make it easier to find music that matches or improves mood.

This project helps to:
* find music that supports the current emotional state
* reduce stress and process negative emotions
* increase motivation, focus, and relaxation

Personal motivation: I want to combine mental well-being and technology in a practical way. Music has always been an important source of emotional support for me.

## How is it used?

The user opens the app and provides information about their current mood by:
* writing a short message,
* selecting an emotion from a list, or
* (optionally) allowing the camera to analyze their facial expression.

The app then recommends a personalized playlist via the Spotify API.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

## Data sources and AI methods

Data sources:
* Spotify audio feature data (tempo, valence, energy, danceability, etc.)
* User-provided mood ratings
* (optional) Emotion recognition model from camera input

AI methods:
* Sentiment analysis for text-based mood detection
* Recommendation algorithm (e.g., k-nearest neighbors or cosine similarity)
* Valence–Arousal model to map emotions to musical attributes

