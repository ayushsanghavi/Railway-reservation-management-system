# Railway Reservation Management System

## Aim : 
To create a user friendly Graphical User Interface (GUI) to ease the process of booking railway tickets, in contradictory to travel to the ticket counter and standing in long queues. 

## Specs :
- Used the python Tkinter library for creating and editing the GUI.
- Connected a SQLite3 database to the portal so that the data is stored in the backend.
- Created a user authentication feature that asks for the username and password. (In the code there are three names that can be used as the username and the password for the same is "844")
- If the credentials are verified correctly, the GUI will popup a successfull login message.
- The user is asked for his desired source and destination of travel. Incorporated the date of travel calender validation. The user is also asked for the class of ticket he is comfortable with. eg: 1A, 2A, 3A.
- Based on the above parameters, a list of trains is shown.
- The user can book the ticket. The data is stored in the database.
- A successful receipt showing all the details correctly is displayed on the screen.
- In case is the user wants to cancel his/her train ticket, he/she can enter the PNR number and fetch the necessary details from the database and cancel it. Cancelling the ticket will delete the entry from the database.

## Tech used:
- Python3
- SQLite3 DB
- Libraries used : Tkinter, time, random
