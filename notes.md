<!-- Project 2: First Drafts: Wednesday 2015-11-04-->

<!-- Technical Requirements: 
Your app must:

Have at least 2 models (more if they make sense) – one representing someone using your application, and one that represents the main functional idea for your app
==> Models: -User 
			-Routine
			-(?Exercise model or exercise_form?)

Include sign up/log in functionality, with encrypted passwords & an authorization flow
==>ATTEND JOE'S DEVISE LECTURE, CONTINUE RESEARCH 

Have complete RESTful routes for at least one of your resources with GET, POST, PUT, PATCH, and DELETE
==>Routines

Utilize an ORM to create a database table structure and interact with your relationally-stored data
==> ROUTINE will have many time stamp, Exercises[exercise_name, description, duration, and option to mark complete]

Include wireframes that you designed during the planning process
==> Lucidchart:
https://www.lucidchart.com/documents/edit/afbebb8d-4046-4eac-92b9-da847ce45645#?=undefined

Have semantically clean HTML and CSS
==>GOAL: BEGIN CSS BY SATURDAY AT 4PM IF RAILS MVP SATISFIED/FUNCTIONAL

Be deployed online and accessible to the public 
==> Review deployment process (Jason lecture Friday?)

============================Short List=====================================
To Do: 

-Create new project repo
-add this md 
-Finish wireframe and user story 
-Decide how to incorporate Devise if applicable. 

============================APP OVERVIEW===================================
-This is essentially a to-do list 
-User can login (or create a new username/account)
-Once in user index, user can create a new workout routine via new_routine_form
-The routine form will ask for a routine_name and timestamp**1, and will have many exercises:	
	-Exercise: exercise_name, description, duration 
-When user hits submit, new_routine.html.erb view is displayed 
	-option to mark exercise complete
	-option to edit/update 
	-option to delete
	-option to return to main page with all listed routines 


**BONUS
1. Date/timestamp: Dropdown? 




