## FEATURES:

User can activate Danger Mode just TAPPING POWER BUTTON MORE THAN 4 TIMES (API level 28 or 29). Which will lead to

1. Call emergency number (999 for BD)
2. Sending messages to the numbers user has set up (As much as user wants)
3. Sending their current location with message
4. User can also get numbers of AMBULANCE, POLICE, FIRE SERVICE of different divisions of Bangladesh and call these numbers straight.
5. User can sign in to his own account and save his information. So next time if he reinstall the app, there's no need to update information twice.

## App demo

<table >
  
  <tr>
    <th>Signup</th>
    <th>Login</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/1-create%20account.jpg">
    </td>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/2-login.jpg">
    </td>
  </tr>
  
  <tr>
    <th>Welcome window after signup</th>
    <th>Home screen</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/3-welcome%20screen.jpg">
    </td>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/4-home%20screen.jpg">
    </td>
  </tr>
  
  <tr>
    <th>Settings window</th>
    <th>Update / Delete contacts</th>
    <th>Advanced settings window</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/5-settings%20screen.jpg">
    </td>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/6-%20settings%20update%20numbers.jpg">
    </td>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/7-advanced%20settings%20screen.jpg">
    </td>
  </tr>
  
  <tr>
    <th>Emergency mode initiated</th>
    <th>After 4+ tap on power button</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/8-emergency.jpg">
    </td>
    <td width=33%>
      <img src="https://github.com/FarhanSadaf/Emergency-app/blob/master/tutorials/9-emergency%20after%20pressing%20power%20button.jpg">
    </td>
  </tr>
  
  <tr>
    <th>Emergency contacts window</th>
    <th>Detailed emergency contacts</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="">
    </td>
    <td width=33%>
      <img src="">
    </td>
  </tr>
  
  <tr>
    <th>Sidebar</th>
  </tr>
  <tr>
    <td width=33%>
      <img src="">
    </td>
  </tr>
</table>

## UNDER THE HOOD:

I used FireBase Authentication to sign the users into the app.

FireBase Realtime Database is also used to store Numbers whom user want to send message in case of emergency and Name of the user.

Map API is used to get current location from GPS, to be precised, latitude and longitude.

JSON format is also used to parse Emergency Ambulance, Fire Service or Police numbers of different divisions.
