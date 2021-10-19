# Mission to Mars

[Web Scraping Function with Splinter and Beautiful Soup](https://github.com/c-geisel/Mission-to-Mars/blob/main/scraping.py)
[Flask File to Create Web Application](https://github.com/c-geisel/Mission-to-Mars/blob/main/app.py)
[HTML formatting Template](https://github.com/c-geisel/Mission-to-Mars/blob/main/templates/index.html)

### Applications Used
Python, Jupyter Notebook, Splinter, Beautiful Soup, MongoDB, Flask

## Purpose
The goal of the following analysis is to gather pertinent information from various websites through web scraping to create an outlet with the most up to date information on Mars. 

## Process
To begin this process first a script is written in Jupyter Notebook that utilizes Splinter and Beautiful Soup to automate a web scraping process. Data is gathered from 4 different websites to find the most recent article title and summary posted, the most recent featured image, a table of Mar’s facts, and images on the different hemispheres of Mars. After we are grabbing this data, a function is created in Python to scrape all desired data in one task. Next, Flask is used to create a web application that incorporates MongoDB to store all the data gathered. Integrated into these files is an HTML index template that is used to structure and design the web application. These files all work together to create a website that we can use to find the most up to date information about planet Mars at the click of a button.

## Outcome 
When the app.py flask file is run the web application is able to be viewed. 

![election_results_txt.png](analysis/election_results_txt.png)

By clicking the "Scrape New Data" Button, the scraping.py file is running our web scraping function to gather the latest data on Mars.

