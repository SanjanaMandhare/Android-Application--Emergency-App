## Introduction
The main goal of this app is to send an alert message to the user in an event of an emergency such as a natural disaster, terrorist attack etc. Also, it will provide users with helpline information such as nearby hospital number, police station number, Fire Services Number, Blood Bank Number etc. and also navigation details to that location so as to help the user help himself rather than waiting for help to arrive and wasting precious time. 

## Project Modules

➢	REGISTRACTION:- In this user can register self-details like Email, Password, conform password etc...   
 
➢	LOGIN:- In this if user already register their self-information, then user can login their     information like email and password. User can sign in to his own account and save his information. So next time if he reinstall the app, there's no need to update information twice. 
 
➢	HOMEPAGE:- After login user reach the homepage.   
 
➢	EMERGENCY CALL:- The app will make an emergency call to all the family members in the event of a major emergency 
 
➢	EMERGENCY ALERT MESSAGE:- The app will send a text message notification to all the family members in the event of a major emergency, so the user does not need to have an active internet connection to receive the notification. 
 
➢	ADD FAMILY CONTACT:- The user can add the family members Contact so the app can send notification and can make call in the event of a major emergency 
 
➢	UPDATE/DELETE CONTACT:- The user can Update / Delete family members contact details. 
 
➢	CALL HELPLINE NUMBER:- User can also get numbers of 
AMBULANCE, POLICE, FIRE SERVICE of different divisions of Bangladesh and call these numbers straight.  


## FEATURES:

User can activate Danger Mode just TAPPING POWER BUTTON MORE THAN 4 TIMES (API level 28 or 29). Which will lead to

1. Call emergency number (999 for BD)
2. Sending messages to the numbers user has set up (As much as user wants)
3. Sending their current location with message
4. User can also get numbers of AMBULANCE, POLICE, FIRE SERVICE of different divisions of Bangladesh and call these numbers straight.
5. User can sign in to his own account and save his information. So next time if he reinstall the app, there's no need to update information t

## UNDER THE HOOD:

I used FireBase Authentication to sign the users into the app.

FireBase Realtime Database is also used to store Numbers whom user want to send message in case of emergency and Name of the user.

Map API is used to get current location from GPS, to be precised, latitude and longitude.

JSON format is also used to parse Emergency Ambulance, Fire Service or Police numbers of different divisions.
