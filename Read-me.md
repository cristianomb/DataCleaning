---
title       : Project Course - Getting and Cleaning Data 
subtitle    : Project Course
author      : Cristiano Martins Barbosa
---

## Description of the script run_analysis.R

The main goal of this script is to process the received data to generate tidy data.

It first reads the train data and binds the columns of subjects and activities. The column
of activities is processed to exhibit the descriptive names of acivities instead of its
numbers. The same is done to the test data.

Then the scripts merges the train and text data. The merged data is divided in groups of activies and subjects and smmarized to generate tidy data. Tidy data is than written to file.

Obs: I couldn´t understand completely what to do in this Course Project. Some steps, such as naming the variables, and 
extracting the standar desviation I couldn´t complete. I´m sorry for that.

---



