# Mission-to-Mars

## Overview of the Project

This project is about building a web application with a built in 'Scrape New Data' button, which ,when pressed, scrapes data from different other webpages and updates our website with latest data regarding the planet Mars.

The purpose of the project is to make a website and automate the process of scraping updated information and presenting in out web application. This way, we can always access the latest news and information about Mars.

## Results

The web application is built using HTML and CSS. Here are the different steps taken to make the web app:

1. At first a few websites were identified which contains the data and images I want in my web app. Afterwards, I user jupyter notebook to test my scraping code to make sure I am retreiving the content I want.

2. Next I converted my jupyter notebook file to a python file and used VS Code to create different functions which could do the different scraping tasks when called. I also had a master function which calls all the scraping functions and adds the results to a dictionary.

3. The dictionary with all the scraped code is uploaded in my database in MongoDB. Our MongoDB database makes it possible for our html and css code to pull the data from there and display it on our web app.

4. Finally, the 'index.html' file contains all our html code to make the website customizations.

## Summary

Going through the steps listed above, I was able to create a website that displays latest news articles about Mars, shows a latest image, contains some comparison information of Mars with Earth and also displays the different hemispheres in Mars. The web app runs successfully and there is a button to scrape new data to update the web app.