This is the codebase for a simple app to allow one to check stock information by connecting to the Quandl API.  The app is written using the Flask web development framework in Python.  The app is hosted on Heroku and can be accessed at:

http://checkyourstocks.herokuapp.com/

The app requests data from the Quandl API (https://www.quandl.com/).  The data is return in JSON format with the requested information (as indicated in the web form by the user).  The data is then stored in a Pandas data frame.  Next Bokeh is used to create an interactive visualization of the data (a graph) to be displayed on the app through Flask.

