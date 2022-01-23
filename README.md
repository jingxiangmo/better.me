better.me is an AI powered personal journal that uses NLP emotion analytics to provide smart mental health recommendations! 

## Problem Statement
Poor mental health is a growing pandemic that is still being stigmatized. Even after spending $5 Billion in federal investments for mental health, 1.3 million adults attempted suicide and 1.1 million plans to commit suicide. 

> Our mission is to provide a private environment to help people analyze their emotions and receive mental health support.

## Product Overview
- Personal Journal <br>
Better Me is a personal AI-powered journal where users can write daily notes reflecting on their life's progress.

- NLP Emotion Analytics <br>
With the help of natural language process, Better Me will classify the user's emotional situation and keep a track of the data.
 
- Smart Recommendations <br>
It uses this monitored data to suggest appropriate mental health resources to the users and also provides them with suitable data analytics.

- Suicide Prevention <br>
In order to take a step forward towards suicide prevention, it also incorporates a suicidal text detection algorithm that triggers a preventive measure .

## How we built it
We used Google T5 NLP model for emotional recognition and categorizing emotions. We trained data set with deep learning to develop a fine tuned BERT model to prevent suicide. We also implemented our own algorithm to make resource recommendations to users based on their emotional changes, and also did some data analytics. Due to time restraints and a member's absence, we had to change from React.js plus Firebase stack to Streamlit, a python library designn framework. 

## Challenges we ran into
Initially, we tried creating a dashboard using full-stack web development, however, it proved to be quite a challenging task with the little amount of time we had. We decided to shift our focus to quickly prototyping using a lightweight tool, and streamlit was the ideal choice for our needs. While deploying our suicide prevention algorithm on Google Cloud Function, we had trouble deploying due to memory availability constraints. However, we were able to solve this issue.

## Accomplishments that we're proud of
We are proud that we came up with such a novel idea that could be useful to innumerable people suffering from mental health issues, or those who are like to stay reserved with themselves or in a confused state about their mental well-being, just by writing about their daily lives. We are also proud of incorporating a suicide prevention algorithm, which could be life-saving for many.

## What's next ?
- Firebase Back End Architecture <br>
     We hope to design a scalable backend which accommodates for the users needs. 

- AI Mental Health Chat bot <br>
     We hope to provide on the spot, mental health support using Dialogflow AI chat bot.

- Connect with Therapists <br>
     We hope to elevate data analytical features to connect and report to personal therapists.

- Scaling Up <br>
    In the future, we hope to fund our project and develop this project with scalable front and back end. 
