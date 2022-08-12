# Movie-Box
Movie Application 

# How to Set Up a React Project
Ok with that out of the way, we can get into the good stuff – creating a React project. We're going to use create-react-app to get us off the ground quickly.

**Fire up a terminal and type:**

`npx create-create-app movie-app`

When thats finished doing its thing, we're going to add Bootstrap to help us position things nicely without needing much of our own CSS.

**Run the following commands:**

`cd movie-app
npm install boostrap`
Thats all we need, so go ahead and fire up the app:

`npm start`

# How to Add Movies to State
The App component will hold the state for the app. That way we can keep everything organised in one place and pass different pieces of state to different components.
# How to Create a MovieList Component
Ah our first component! We're going to create a MovieList component to display the list of movies that comes back in the search request.

**Create a new folder** call **components under the src folder.** Create a new file in the components folder called **MovieList.js:**
