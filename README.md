# Webscraping_UK.Indeed_BeautifulSoup
it's a program that retrieves data from websites and parses it for specific data. In this project, the website, Indeed.com a popular job search website is going to be used for scrapping data.
it is important to understand the structure of the URL before scrapping.
URL : https://uk.indeed.com/jobs?q=data+scientist&l=London%2C+Greater+London&start=3
here,
*  ‘q’ is the string for the position which is wanted to be searched for a job. in this project, I am going to search for the position data scientist.From the above URL, q will be equal to the string Data Scientist separated with the ‘+’ sign.
* ‘l’ is the string for the location or city I want to search. In the above URL, it is ‘London & greater London’.

* The ‘start’ denotes the result from I where you want to begin with the scrapping. In this URL, it is 3.

## Installing the required libraries:
* pip install requests
* pip install bs4

## Steps: 
* Send an HTTP request to the URL of UK.indeed using HTTP library for python-requests. The server responds to the request by returning the HTML content of the webpage.

* After accessing the HTML content, the next step is parsing the data to create a nested/tree structure of this HTML data. 

* The final step is navigating and searching some specific data such as company name, location, salary and job summary using library, Beautiful Soup.
