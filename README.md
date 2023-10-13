# mariahgammonartifact

https://rpubs.com/mariahgammon/1098493

# Introduction
The current state of research in data driven marketing in animal shelters is that animal shelters do not currently utilize data to help them drive marketing enough. I found is that only about half of the animals that are placed in shelters per year are adopted out of them - 3.2 million out of 6.5 million, and many animal shelters are at capacity and/or overpopulated, resulting in many animals not being homed, not being sheltered, or being euthanized. My research tells me that shelters do not use enough data analytics to determine why people adopt pets, which pets are more likely to be adopted based on types of marketing efforts. Why do some pets get adopted and others don’t? Could increased focus on data and improved marketing help more animals get adopted out of these shelters?

For now, I have been focusing on using R Studio & Quarto to analyze intake & outtake data in animal shelters into a Quarto Document.
Quarto and R Studio are efficient ways to create graphs and trends in one, central location to then be able to analyze and tell a narrative throughout.

The .qmd file is the code that I used to run the project in R Studio.

# Technical Details

Use R, Quarto, and Shiny apps to create the data & analytical aspects of the project
Tell a strong narrative and connect the data to the knowledge gap/research questions
- could go in direction of looking at costs of keeping animals at capacity/overpopulation for long periods of time or hopefully show connections with marketing data (Animal Friends Animal Shelter)
Give animal shelters aid in keeping, collecting, and analyzing data (as of now, they do not really analyze those resources but have interest in it)

# How to Run/View Project
https://rpubs.com/mariahgammon/1098493 - this is the link to the current published website with the graphs & code
If you follow to that page, a publicly available document with the graphs and trends based on the CSV file Animal Shelter Intake and Outcome data is available to view.


However, if you want to run it locally, you would need R Studio on your device.
You would need to download libraries in the console:
library(ggplot2)
library(dplyr)
library(shiny)
library(quarto)
