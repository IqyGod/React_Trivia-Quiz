# React_Trivia-Quiz

## Table of contents
* [App Link](#app-link)
* [General info](#general-information)
* [Stretch Goals](#stretch-goals)
* [Technologies](#technologies)
* [Add Features](#add-features)
<br>

## App Link
https://1andmore-funquiz.netlify.app/
<br>

## General information
<img src="https://user-images.githubusercontent.com/99662300/179439179-0420975d-9409-4224-96ac-46dc342bc896.png" width=25% height=25%> <img src="https://user-images.githubusercontent.com/99662300/179439533-ec39ab6d-040a-4e4d-9040-bfa457e43c71.png" width=25% height=25%> <img src="https://user-images.githubusercontent.com/99662300/179439335-40f233ea-dd18-40dd-95cf-b0ad33b42555.png" width=25% height=25%>


This game application was built based on React, with: 
- Component
- Props
- State
- Hooks

2 significant hooks are used here : useState, useEffect.
<br>-  __useState__: 
<br>state will hook into the component
- [quiz, setQuiz] ==> retrieve data from API
- [score, setScore] ==> track number of right answer
- [clickCheck, setClickCheck] ==> manage state of "check" button
- [isStartOver, setIsStartOver]

<br>- __useEffect__: 
<br >it can be the place to side effect code
- fetch data from OTDB API and store data into quiz to mapping questions and answers.
- sync 2 internal states (this function yet working)

<br>Add __events listeners__ :
- choose answer
- to check answers
- start new game

<br>

## Technologies
- React
- HTML
- CSS
- JSX

<br>

## Stretch Goals
- As a user, they can start the game by click "start quiz" in introduction page.
- As a user, they can held the right answers and click check to tally correct answers. The color will declare whether it is correct. (red - no, green - yes)
- As a user, there can restart the game.

<br>


## Add Features
- As a user, they receive confetti after archive 5/5 score in the game. (this function yet working)
