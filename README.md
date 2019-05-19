# PWP SPRING 2019
# PROJECT NAME:
Team Sports
# Group information
* Student 1. Sampo Niittyviita, sampo.niittyviita@student.oulu.fi
* Student 2. Saroar Jahan, saroarjahan.bd@gmail.com
* Student 3. Markus Turtinen, mturtine@gmail.com

# Client Descriptions
We have developd a working  web client  to test our API. Our Client do not requires any additional  dependencies becasue its developed by  HTML, CSS and  Javascripts Language. More specificly, we have used <a  target="_blank" href="https://vuejs.org/">vue.js</a> for our forntend management. In addition, we have used <a target="_blank" href="https://vuejs.org/v2/cookbook/using-axios-to-consume-apis.html">Axios</a> library to fecth client with our API.

# External API
We have used to two external API to work with our own API.
1. Google Map API: have been used to show location of the Events and auto fill-up location during adding new events.
2. Weather API used to show wather based on event location.

# API Resources Implemented in Client
Total 4 resources and 9 API request implemented in the client.<br>
1.api/users/ (GET, POST)
2.api/users/<user_handle>/(GET,UPDATE, DELETE)
3.api/users/<user_handle>/events/ (GET, POST)
4.api/users/<user_handle>/events/<event_handle>/(GET,DELETE)


# How to Test client
1. No additional setup needed, make sure we are running Main restfull api in http://127.0.0.1:5000/<br>
1. Visit  client_team_sprots > Templates repository<br>
2. Run Index.html file with chrome or any modern browser<br>
4. client will automatically fetch the url of rest api <br>

# Client Repository Description
1. Static- contains css, images, some javascript libraries 

2. Templates: Contain templates of the client. Here we have used...<br>
	-index.html for showing all events, update and delete events<br>	
	-add_events.html for submiting/creating new events<br>
	
	-all_members.html for showing all members, creating, updating and deleting individual members

3. JS- this repository contains 3 javascripts files that follow vue.js library format coding.<br>
	-appEvents.js controll action of getting all events by GET request, Delete an event by DELETE request<br>
	-appAddEvents.js controll action of cretaing new events by sending POST request<br>	
	-appMember.js controll action of getting all member by sending GET request, creating new member by 
	 POST request, Updating member details by PUT request and deleting an member by DELETE request.





