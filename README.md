# W3-HW3--Starships-

Intro
In the lesson earlier you:

Learned to consume a third-party API in React and invoke the call to that API using the useEffect hook.
Organize State with the useState hook.
In this lab, you'll consume the Star Wars API (Links to an external site.) and render its data.

 

Set Up
To get set up for this lesson:

Use create-react-app to create a React app named react-star-wars
cd into react-star-wars and open VS Code.
Open a terminal in VS Code.
Start the React Dev Server.
 

 

 

Exercises
Styling in this lab is secondary to completing the functionality

Research documentation of SWAPI (Links to an external site.) to find the endpoint for the starships resource.
Use the fetch method to make requests to at least one endpoint
Obtain all of the starships from the API and render in <App> a card for each starship.
Cards should contain the text of the starship's name.
Make use of routing with React Router v6 by creating a working navigation bar (npm install react-router-dom) 
 

 

 

For example:



Hints
Hold the starship objects in state with the useState hook, don't forget to initialize to an empty array!
Use the useEffect hook to make the AJAX request once the app loads.
Once the starship data comes from the API, be sure to update state with the setter function.
Create and import a StarShipCard component into App.js.
.map() over each starship object in state to transform them into a <StarshipCard /> component
CORS issue? Try changing your /starships endpoint to /starships/ 👈 trust us on that one 😎.
 

 

 

Bonus
Display additional details for each Starship in it's respectable card.
This API has a pagination feature that allows you to get additional starships to display - find out how to use this to your advantage and allow users to get more starships at the click of a button
