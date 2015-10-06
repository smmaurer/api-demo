# Introduction to APIs

Guest presentation for UC Berkeley CP 255 - Urban Informatics  
October 7, 2015

This demo introduces [APIs](https://en.wikipedia.org/wiki/Application_programming_interface), which are code-based interfaces that allow outside developers to interact with a piece of software. We'll focus primarily on data-access APIs that operate over the web. In class we'll use Python to connect to a variety of APIs, from earthquake feeds and geocoders to public social media posts.


#### Before class

1. **From the command line, install this Python package for connecting to Twitter APIs:**  
   `pip install TwitterAPI`  
     
   There are several different package managers for Python. We're using "pip install" instead of "conda install" because Anaconda doesn't include this package in its index. 
   &nbsp;

2. **Make sure `keys.py` is in the same directory as this notebook**  
     
   `keys.py` (provided separately) contains demo authentication keys for the Twitter APIs. For folks not taking the class, you can edit the `keys-example.py` file, following the instructions in the next step to obtain your own credentials.  
   &nbsp;

3. **Look over some of the resources that companies and public agencies put together for third-party software developers, for example:**

	* BART: http://api.bart.gov/docs/overview/index.aspx
	* Twitter: https://dev.twitter.com/overview/documentation
	* Google Maps: https://developers.google.com/maps/get-started/  
	&nbsp;
   
3. **OPTIONAL: Sign up for your own Twitter API credentials (5 minutes)**  
     
   Twitter limits the number of simultaneous connections from a single account, so if you're willing to sign up for your own credentials, it will help the in-class demo go smoother!  
     
   * Log into Twitter or create an account: http://twitter.com  
     &nbsp;
     
   * Register a new app development project: https://dev.twitter.com/apps/new  
     &nbsp;  
     (The form is geared toward people making smartphone or web apps, but you still have to fill it out... You can call the app an in-class demo and give the URL of your own Twitter page, for example)  
     &nbsp;
     
   * Submit the form, go to the "Keys and Access Tokens" tab, and click on "Create my access token" at the bottom of the page  
     &nbsp;
     
   * Copy these four codes into the `keys.py` file, replacing the demo credentials:  
     (a) consumer key, (b) consumer secret, (c) access token, (d) access token secret  
     &nbsp;
     
   * All done!