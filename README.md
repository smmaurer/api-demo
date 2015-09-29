# Introduction to APIs

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

