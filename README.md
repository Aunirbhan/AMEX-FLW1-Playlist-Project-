# Unit 2 Project // Playlist [Light]

## Overview:

In this unit, coders will create a playlist. The playlist will display a list of information about different songs with images and links to play the songs.

To create this project, coders will create arrays to hold song information, use a for or forEach loop to iterate over the arrays, and display data to the screen.

They will use .push to add new songs to their playlist. Then, students will refactor their project to using objects instead of arrays to hold their data.

## Set-Up

- [x]  Fork your own copy of the repl.
- [x]  Double-check that you are signed in with your GitHub account.

## Planning

- [x]  Complete the planning document.
    - [x]  Look over Inspiration and Ideas
    - [x]  Fill out the Brainstorm section.
    - [x]  Fill out the Song Data section.
- [x]  Read through the HTML starter code to understand the organization and class names given.
- [x]  Read through the JavaScript starter code to determine where each given function is declared and where each given function is called.
- [x]  Declare variables for your display divs: the image url, song name, artist, and song link. Go back to the HTML to check that you are using the correct class names.

## JavaScript: Storing Song Data

- [x]  Create and populate an array to store your image urls. Create three more arrays. One to store your song names, one for the artists, and a last one for the song links.

## JavaScript: Loop and Display Data

- [ ]  Loop through your images array and display the images to your songs in the correct div. Create three more loops. One for the song names, one for the artists, and a last one for the song links.

What to display your song data in:

- images: `<img>` tag inside a `<p>` tag
- song names: `<p>` tag
- artist: `<p>` tag
- song links: `<a>` tag inside a `<p>` tag

**Note**: There is a function called `emptyDisplay`. Determine where this should be placed in your code. Where does it make sense to call this function?

## JavaScript: Add Song Data

- [ ]  Declare a variable to save the user input of the image url. Declare three more variables that save user input: One for the song names, one for the artists, and a last one for the song links.
- [ ]  Use `.push()` to add each input value to the correct array.

## JavaScript: Refactor Arrays to Objects

- [ ]  Comment out the arrays data.
- [ ]  Create an object for each of your songs.
- [ ]  Inside each object, add key/value pairs to store the image url, song name, artist, and song link.
- [ ]  Create an array that stores all of the objects.

## JavaScript: Refactor Loops to Display Info

- [ ]  Update your `addSongInfo` function so the input values are saved in as values in a new object.
- [ ]  Update your `.push()` so the input object is added to your array of objects.
- [ ]  Update your loops based on your new array of objects.

## Project Extensions:

- [ ]  Add in your own CSS to personalize your project.
- [ ]  Use .length to display how many songs are on your list.
- [ ]  Add a clear or delete button to clear songs on your list.
- [ ]  Refactor your project further by utilizing functions to simplify your code.
- [ ]  Add a shuffle button and functionality.