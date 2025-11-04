# my-new-project
Building Ai course project
# SmartTrainer AI

Final project for the Building AI course

## Summary

SmartTrainer AI is an application that analyzes an athlete's training performance and provides personalized suggestions for improvement. The goal is to help users train more effectively, avoid injuries, and track progress in a clear and motivating way.

## Background

Many people aim to improve their athletic performance, but:
* It’s difficult to know whether you're training correctly
* Mistakes in form can lead to injuries
* Progress may stall without proper adjustments

This problem is common among both beginners and advanced athletes. My personal motivation is to make coaching support more widely available. Not everyone can afford a personal trainer but many still want to train safely and efficiently.

## How is it used?

SmartTrainer AI can be used during or after a workout:
1. The user records their movement using a phone or wearable tracker.
2. The app analyzes the movement pattern using pose estimation.
3. Feedback is given in simple, actionable form (e.g., “lower your shoulders”, “increase step tempo”).
4. The app suggests improvements and progression plans based on goals.

Example use cases:
* Gym strength training
* Running technique feedback
* Rehabilitation tracking
* Sports skill development (e.g., tennis swing, football kicking form)

<img src="https://training.fit/wp-content/uploads/2020/03/kniebeugen-langhantel-800x448.png" width="400">

## Data sources and AI methods

**Data sources:**
* Motion capture / video tracking using phone camera
* Wearable fitness tracker data (heart rate, cadence, acceleration)
* User input: goals, training history

**AI methods:**
* Pose estimation (e.g., MediaPipe, OpenPose)
* Movement classification & form detection (pattern recognition)
* Progression recommendations using simple machine learning regression models


