This is a webapp to host fate-go info and calculators

Development guide:
All the code is in fatego-app/

So far, this uses Python Flask and Skeleton CSS. Link to docs:
http://flask.pocoo.org/
http://getskeleton.com/

MVC docs:
https://code.tutsplus.com/tutorials/mvc-for-noobs--net-10488

Example model: implementation of damage calculator
Example view: landing page
Example controller: Nothing yet l0l

To test:
$ fatego-app/run.py
Then go to browser and go to localhost:9001

Directory overview:
static/: place static files (images, css) in here.
templates/: templates for Flask go here. Templates are separated by type, i.e. templates/landing will hold the templates for the landing page
views/: views are 
