# BeepTweet
This respisotory is based on a final project in Hands-on AI course in University of Hong Kong where our team created an AI program BeepTweet which detects emotion from tweets and generates music based on emotion. 

## Contents
  - [Brief presentation](#brief-presentation)
  - [Project report](#project-report)
  - [VAD values model](#vad-values-model)
  
## Brief Presentation

BeepTweet is an AI model which targets entertainment and social media platforms like Twitter as a bonus feature for a tweet or any short text. The question we ask is how would a text sound like? We managed to create a program which creates short clips of music or sounds based on the emotion behind text. BeepTweet consists of 2 main parts:
  - Emotion detection from text or in broader terms NLP model
  - Music generation model

To make our project more available to general public we made a concise presentation on how our program works.
- [Here you can find the video](https://drive.google.com/file/d/1Mak4EzkhuPrDwkPjo4QFPjdckPdOaY4o/view) <br />

Here we talk about how the model works and put emphasis on how we created it:
- We talk about what data sets we have used
- How we created our own annotated data sets from Twitter API
- The combination of various different data sets
- Exploratory data analysis
- Different feature extraction experimentations
- What machine learning models we have tried out
- Hyper tunning
- Error Analysis
- Evaluation
- Limitations


## Project report

[Here](https://github.com/justsvykas/BeepTweet/blob/main/Project%20report.docx.pdf) you can find final project report where we talk more extensively about BeepTweet

## VAD values model

In this part of the project we determined the emotion behind short text. We created 2 models to make use of various music generation models:

- Categorical values model
- Dimensional values model <br />

In this section of the notebook we will focus on dimensional values. Every emotion can be put in 3 dimensional values:
- Valence
- Arousal
- Dominance

![VAD_visual](https://github.com/justsvykas/BeepTweet/blob/main/VAD_visual.png)

[Here](https://github.com/justsvykas/BeepTweet/blob/main/VAD_model/Main_Ridge_regression.ipynb) you can find our code on how we determined VAD values from text
