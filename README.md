# Picture-Shuffler
Project: Web Application created using HTML / CSS, PHP, MySQL, JavaScript
The project consists into a Web App that allows users to preview and post infos, presenatations, etc on selected TV's in the company. 
In the company every person had an unique code in a daatabase so in order to not let the whole company to post infos on the TV's, the users table is independent and every user should be created by admins.
When creating a new user, the admin selects the departments where he is allowed to post infos.
The users are allowed to post only on TV's from their department or on the departments they have access (example: IT department can post in HR or Incoming Department but HR or ID are not allowed to post on TV's from IT department)
The communication with the TV's was made via IP. 
The info that users are posting is constrained by dates. Example: A poster should be shown from date X until date Y. So every info is checked if the actual time is between X and Y. 
The functionality that was implemented with JavaScript was the timer for each info displayed. 
Every info posted has a display time and so I implemented a timer in the corner of the screen where appears the time selected for displaying and the time left until next info appears.
