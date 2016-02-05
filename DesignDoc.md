#Project Goal
The goal of the project is to facilitate drawing as a means of communication. This means that drawings should be able to be made and shared quickly and easily. 
 
--
 
#Scope

This project WILL:

1. To provide a tool through which the User can create drawings and share them as easily as possible.
2. Provide a space where Users can post their drawings.
3. Be accessible and work on desktop and mobile devices.

This project WILL NOT:

1. Allow the User to upload anything to the server. All assets will be created on the site.
2. Allow for plain text as a means of communication. Text will only be used when absolutely necessary, such as for usernames and passwords

--

#System Overview
On the server, there are two primary pieces of data: Users and Drawings:

* **Drawings** contain information about images drawn by a User in the system.
* **Users** contain information about individuals who use the system. Users have lists that store their Drawings, and a list of friends that holds other Users.

The client is able to interact with these data types through the following interfaces:

###Creating Drawings

**1. Drawing Page**

Description:
The User uses this page to create a drawing. 

Minimum Requirements:

* The User can draw on a canvas
* The User can save a drawing
* The User can share the drawing on the social media sites of their choosing

Stretch Goals:

* The User can set privacy settings for the drawing, such as "Self", "Friends", "Friends of Friends", and "Everyone"

###Creating Users

**2. Registration Page**

Description:
This page creates a User

Minimum Requirements:

* Displays a form where the User can enter a username, and a password
* Upon submitting this information, the system checks to see if the username is taken:
	* If not taken, create the user
	* If taken, return an error

Stretch Goals:

* Allow the user to create a profile picture

**3. Login Page**

Description:
This page allows a user to login for the session

Minimum Requirements:

* Displays a form where the User can enter a username, and a password
* Upon submitting this information, check it:
	* If the username exists and the password is correct, log them in for the session
	* If the username and/or password is incorrect, return an error

###Displaying Images

**4. Main Timeline Page**

Description:
Displays a Timeline of Drawings from the User and their friends in sequential order.

Minimum Requirements:

* A timeline loads all drawings that you and your friends have made in the order they were published
* clicking on a drawing will reveal options for sharing the drawing and liking the drawing

Stretch Goals:

* the user can reply to a drawing with another drawing

###Displaying Users

**5. User Timeline Page**

Description:
Displays a timeline of all Drawings that the User has created or shared

Minimum Requirements:

* A timeline loads all drawings that you have made or shared in sequential order

Stretch Goals:

* the user can reply to a drawing with another drawing

--

#Timeline

###Planning Phase: Weeks 1-2

Deliverables

* Design Document
* Wireframes

###Front-end Phase: Weeks 3-6

Deliverables

* React Component Library and Basic Front-end

###Individual Back-end Phase: Weeks 7-10

Deliverables

* Backend allows a User to create and save images
* Dummy Data for testing

###Network Back-end Phase: Weeks 11-14

Deliverables

* Users can interact with other Users

###Presentation Phase: Weeks 15-16

Deliverables

* Write-up of my research
* Presentation Slides
* Last-minute tweaks