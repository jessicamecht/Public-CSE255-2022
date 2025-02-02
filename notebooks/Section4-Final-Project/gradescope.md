# How to use the autograder

Go to https://www.gradescope.com/ and enroll in CSE 255 (please sign in with your student email and use enrollment code 7GVWK2)

Go to HW 5 and submit your files. You will be re-routed to a page where the autograder results will appear, as soon as they finish processing.

## There are three files to submit

results.csv — your predictions on the random test set 

results_country.csv — your predictions on the country test set 

code.zip — your code in a zip file

## Each csv file should have the following columns

filename — e.g. image13724.npz

urban — 1 when urban, 0 when not urban

label  — predictions of -1, 1, and 0 when I don’t know

label_accuracy - predictions of -1, 1 

## Evaluation 
You will be evaluated on different test cases, that will also appear on a class leaderboard. You can choose an anonymous name for the leaderboard. Please note that the asymmetric loss can be a value between -2 and 1, and appears in the leaderboard that way. In your evaluation test cases, this value is mapped to a number between 0 and 10 so that you don't get negative points.

## Number of submissions per day
If you made too many submissions within the past 24 hours, your next submission will have 0 score. However, you don’t loose your best score — just go to your dashboard and you will find a button called submission history on the bottom. Select your the submission you want to have counted. This will also make this submission appear to the leaderboard.