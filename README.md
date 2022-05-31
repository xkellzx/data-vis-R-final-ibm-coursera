# data-vis-R-final-ibm-coursera
Final Project for Data Visualization with R by IBM on Coursera
By Kelly Zeng

Files
adult.csv - dataset used and given for project 
ui.R - R code for generating the layout of the dashboard
server.R - R code for creating the server logic of the dashboard

Dashboard link: https://xkellzx.shinyapps.io/datavis-ibm-coursera-final/

Project Description

Objectives
You work for a company who provides career services for those with lower incomes. The marketing team has a small budget and wants your help to find out which demographics (age, education, gender, etc) to target advertise to in the US. You will create an interactive dashboard with Shiny to explore census data to figure out what trends in different demographics you can find and tell the marketing team your findings.

Dataset Used
The dataset you will use is the UCI Adult dataset. The dataset was taken from the Census database and contains demographic information on people. The variables you will focus on are:
- native_country: the person's native country
- age: age of person
- hours_per_week: number of hours the person works per week
- education: education level
- workclass: class of work like federal government or private etc.
- sex: male or female
- prediction: the income level, either "<=50K" or ">50K", you will facet your graphs by this variable

Goal
Create a dashboard with the UCI Adult dataset that can give insight on the following questions:
- Does education level impact the salary?
- Impact of age and sex on salary?
- People from which native countries are given less income in spite of having good education?
- Does number of hours working contribute to less income?
- Which workclass faces less income?
