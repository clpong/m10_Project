Data Science Capstone project
========================================================

Prepared by : clpong

Date : Monday 6th June, 2016

Overview
========================================================
 
The main goal of this capstone project is to build a shiny application that is able to predict the next word.It meets the requirements of below: 
  
- Satisfy requirement of predicting the next work given an input n-gram
- Ease of use
- Exploring different prediction algorithms

The Applied Methods & Models
=============================
This exercise was divided into seven sub tasks like data cleansing, exploratory analysis, the creation of a predictive model and more.

- Sample data has been cleanned by conversion to lowercase, removing punctuation, links, white space, numbers and all kinds of special characters.
- It was then tokenized into so-called n-grams. 
- The resulting data tables are used to predict the next word in connection with the text input by a user of the described 

How the app works
=================
1. User inputs a word or phase.
2. The application will look for the last 1-4 words in phrase
3. The application will checks from the data table for word/phrases that match
4. The application will compile all the possible predicted words and displays the most likely one

How to use the app:
===================

* Classic mode: Type into the text field, and click the button
to see the predicted next word.
* Instant mode: Type into the text field, and wait. The app
automatically displays the predicted next word.
