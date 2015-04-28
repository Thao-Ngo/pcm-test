# Programmer Compeency Matrix (PCM) app with BackboneJS with PubNub

## Introduction
This code demonstrates how to integrate BackboneJS with PubNub Javascript SDK to build an application.
This application is a Programmer Competency Matrix form which allows a user to rate himself on different programming and software engineering 
competencies. Additionally in this application, the user also gets to see the aggregate scores for each competency level which is updated in realtime.

## Usage
1. Head over to the following link to open the app

  shyampurk.github.io/pcm-test

2. Follow the instructions at the top to fill and submit the form

3. Hover the mouse on the cells to see the aggregate scores for each competency level. Alternatively , open multiple instances of app on browser windows or devices and see the realtime updates on aggregate scores on submission from one of the app instances.

## Pitfalls
1. The app does not support user login
2. This app does not gracefully handle concurrent submissions from two or more users as there is no mechanism to persist the aggregate score data. Such cases may lead to inconsistencies in the aggregate scores.

