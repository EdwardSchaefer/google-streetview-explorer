This application helps users easily construct URLs for Google streetview 
static images.

#Attribution
------------

Based on code from Google documentation at the URL listed below:
https://developers.google.com/maps/documentation/javascript/examples/streetview-events 

#How to Run the Application
---------------------------
To run the application, simply clone the repository, then open index.html. 
Be sure to have your API key.


#List of Files
--------------

	*index.html: The HTML page the application is rendered on
	*README.md: this readme file

#List of Changes
----------------

	*9/13/2017 - Inital commit
	*9/13/2017 - Added attribution to README.md
	*9/13/2017 - Removed superfluous link to API script to remove warning
	*9/13/2017 - Removed code and HTML for links table
	*9/13/2017 - Edited CSS styling for new windows
	*9/13/2017 - Added map element, initialized map and panorama to Baltimore
	*9/13/2017 - Synchronize map and panorama
	*9/13/2017 - Static streetview URL dyncamically generated
	*9/15/2017 - Rounded lat/lng pairs to 7 decimals
	*9/19/2017 - Added preview window img element
	*9/20/2017 - Added input element and button to enter address
	*9/20/2017 - Modified goToAddress function to geocode address
	*9/21/2017 - Modified goToAddress function to change panorama position, 
		globalized some variables
	*9/22/2017 - Added cell that displays zoom level