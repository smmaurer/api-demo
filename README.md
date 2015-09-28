# Introduction to APIs

Sam Maurer  
Guest presentation for UC Berkeley CP 255 - Urban Informatics  
October 7, 2015

This demo introduces [APIs](https://en.wikipedia.org/wiki/Application_programming_interface), which are code-based interfaces that allow outside developers to interact with a piece of software. First we'll explore APIs for querying government datasets. Then we'll use Python to connect to the Twitter developer APIs and search public tweets for words, hashtags, locations, and other attributes. 


#### Before class

* Install the TwitterAPI Python module, sign up for API key (details to come)

* Optional but highly recommended: look over some of the resources that companies and public agencies put together for third-party software developers, for example:
	* BART: http://api.bart.gov/docs/overview/index.aspx
	* Twitter: https://dev.twitter.com/overview/documentation
	* Google Maps: https://developers.google.com/maps/get-started/


#### Presentation outline

* What is an API?
	* code-based interface for outside developers to interact with a piece of software
	* static software libraries vs. web services vs. APIs for data
	
* Data APIs 
	* mechanics: url endpoint, http request
	* Census, Socrata, transit, earthquakes, weather

* Interactive demo part 1
	* API queries in a web browser
	
* More concepts
	* data formats: JSON, XML
	* authentication
	* representing state (eg REST)
	* Twitter API
	
* Interactive demo part 2
	* API queries in an IPython notebook
	* focus on Twitter, but examples of others too 


#### After-class exercise

* Use an API to download some data that you're interested in
* Visualize the data as a map in CartoDB or GIS, or as a chart in Excel
* Write up and submit a brief (~1 page) blog post or report including: (1) how you got the data, (2) an image of a visualization, and (3) what you learned from the data
