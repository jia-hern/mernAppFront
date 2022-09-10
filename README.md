# Places app

Simple mern project about places.

## Functionalities of this app

User can login/sign up to at the Login tab.<br>
All users tab is accessible without authentication,<br>
which shows a list of users.<br>
&emsp;> clicking on this user would show the places that user has created.<br>

After logging in / signing up, users can:<br>
-add a new place with the add place tab<br>
&emsp;> validates title, description, address, image url.<br>
-see existing list of places he/she created,<br>
by going to the my places tab :<br> 
&emsp;> view on map button shows the location on google maps (using google maps api)<br>
&emsp;> edit button to edit details of the place<br>
&emsp;> delete button to delete the place<br>
&emsp;> Logout of the app<br>

## Running the project locally.

1. download and unzip project.<br>
   open the project in a code editor e.g. Visual Studio Code.<br>
   Requires npm and node.js on your development setup.<br>

2. rename .env copy to .env (using this file for development)<br>
   rename .env.production copy to .env.production<br>
   (using this file for production)<br>

3. Requires google maps api<br>
   (both frontend and backend can use the same key)<br>
   Sign up at: `https://developers.google.com/maps`<br>
   create a new account, then enable the geocoding api and maps javascript api.<br>
   Go to the Credentals tab and copy that api key<br>
   Replace the value of REACT_APP_GOOGLE_API_KEY in:<br>
   &emsp;.env<br>
   &emsp;.env.production<br>

4. In the terminal, type in:
   &emsp;npm install (install dependecies)<br>
   &emsp;npm run start (run the project locally)<br>

