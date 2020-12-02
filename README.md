# CSE007 Social Network Analysis project
This is the final project for CSE007. The goal is to explore a dataset of Weibo status created by Weibo users in 2012. All the statuses are geolocalized and attached to a location. You will need to answer 3 questions about the data using Java programming. 
### Objective 
The objective of the project is to get the assignment fro GitHub, clone the project and build a java program that answer **_3 questions_** from the data. You need to choose one question in each category: one about the **status**, one about the **user** and one about the **location**.
### How and When
The project has to be pushed on GitHub where it will be reviewed by the course professors. It is due **Sunday 20th of December midnight**.

Evaluation will based on the answer to the questions for 50% and the coding style and strategy for 50%. The style in particular has to pass the grade check (grade → verification → check). 
We do not provide testing for the answers so you have to rely on your common sense to evaluate your answers. 
### Data
The data has been harvested in 2012 by UTSEUS institute in Shanghai. It is a collection of 504,688 Weibo **Status** published by a **User** in a specific **Location**. Each property is a column of a _csv_ file. The properties are as follow:
1. Status related
	- `status_id` – a unique id for a status
	- `status_datetime` –  a date time in the format ISO 8601 with timezone (YYY-MM-DD HH:MM:SS+UTC)
	- `status_text` –  the text of the status written by the user
2. User related
	- `user_id` –  a unique id for a user. A User can write several statuses
	- `status_gender` –  the gender of the user as described by the user itself
	- `user_friends_count` –  the number of friends for this user
	- `user_followers_count` –  the number of followers for this user
	- `user_status_count` –  the number of status posted by this user
	- `user_favorites_count` –  the number of favorite Weibo status for this user
	- `user_description` –  a short bio written by the user
3. Location related
	- `location_id` –  a unique id for this location. There can be multiple status at the same location
	- `location_name` –  name of the location
	- `location_latitude` –  latitude of the location as a float number
	- `location_longitude` –   longitude of the location as a float number
	-  `location_street` –   name of the street 
	-  `location_category` –   category of the location in English
	-  `location_checkin` –  number of checkin by users in this location
	-  `location_distinct_checkin` –   number of checkin by distinct users  in this location
The CSV file itself is pretty big so it has been compressed as a zip file.
### Questions
Questions are spread into 3 groups of questions. You need to select one question in each category. Be careful, some question require you to normalise if you want relevant results! Some are also difficult BUT you will get higher leniency if you do choose them. 
1. Question about **STATUS**
	1. What day of the week has the more statuses?
	2. What hour of the day is the most popular to post status?
	3. What is the favorite emoji ( 😂) in status text?
	4. Do the 5% most popular users use more or less emoji that the 95% rest?
	5. Do men and women have the same peak hour for posting Weibo statuses?
2. Questions about **USERS**
	1. Is there most statuses by women or by men according to this dataset?
	2. Are the 10% most friendly users posting more statuses than the 90% rest
	3. Are you more popular if you have a longer description of yourself?
	4. Do men have more or less followers than women?
	5. Do the 5% most popular users use more or less popular location that the 95% rest?
3. Questions about **LOCATION**
	1. What is the most popular location category is this dataset?
	2. What is the most popular café in Jing’An district (west: 121.4231, east:121.4479, north:31.3230, south:31.2173) according to the statuses count of users?
	3. How many statuses where posted on Huaihai middle road (淮海中路)?
	4. What is the name of the location where users came back the most?
	5. What is the most popular location on Donhua Campus?
