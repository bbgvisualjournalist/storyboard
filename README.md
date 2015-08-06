# storyboard
Super simple web application for creating storyboards from a Google spreadsheet. 

###Why?
I was tired of creating storyboards in Illustrator or InDesign and making updates when people changed the script. By using a Google spreadsheet, editors can make changes and the panels will automatically reflow.

###How it works
Use the [spreadsheet template](https://docs.google.com/spreadsheets/d/1-bneR4tNaWpbxV7SZ8SqLxQobHpFtQLqg8ATGqpYx5c/pubhtml) for creating a new storyboard. 

Define the project info on the 'config' sheet, then add the voice over script, descriptions for each panel, links to the images in the 'storyboard' sheet. 

Then publish the spreadsheet to the web and include the URL for the published spreadsheet in the HTML (or as a query string ?sheet= ). 

I've added some basic print styles so it should look ok when you print it out, but you'll want to use Chrome because I'm placing the panel images as background images to make them responsive AND keep them 16:9.
