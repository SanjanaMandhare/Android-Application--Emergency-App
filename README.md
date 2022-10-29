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
