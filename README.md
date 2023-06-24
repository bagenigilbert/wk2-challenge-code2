# wk2-challenge-code2
## Phase-1 Week-2 Code Challenge
In this code challenge you are required to create a mini app, Flatacuties, where you can vote for the cutest animal! You will use a local API and build out the frontend for our app.

## Learning Goals
create a mini project app to practice on this that follows:

*DOM
*Server communications.
*Events
*array iteration

## Requirements
For this project, you must:

*Have a well-written README file.
*Fetch data from a local server running JSON DB server.

## Project Setup 

## Project Setup & Pre-requisite Data
In your project directory, create a db.json file and use this data Links to an external site. for your server DB.
Run this command to get the backend started: json-server --watch db.json
Test your server by visiting this route in the browser: http://localhost:3000/characters
## Project Setup
Create a new project folder.
Create a new GitHub repository (NB: ENSURE IT IS PRIVATE).
Add your TM as a contributor to the project.
Please make sure you regularly commit to the repository.
## Project Guidelines
Your project should conform to the following set of guidelines:

## Core Deliverables
As a user, You should:

See a list of all animal names. You will need to make a GET request to the following endpoint to retrieve the character data
GET /characters

Example Response:

[
  {
    "id": 1,

    "name": "Mr. Cute",

    "image": "https://thumbs.gfycat.com/EquatorialIckyCat-max-1mb.gif",

    "votes": 0
  },

  {
    "id": 2,

    "name": "Mx. Monkey",

    "image": "https://thumbs.gfycat.com/FatalInnocentAmericanshorthair-max-1mb.gif",

    "votes": 0
  }
]
Click on an animal’s name to see its details i.e image and number of votes. Note, you should only be displaying the details of one animal at a time. You can either use the character information from your first request or make a new request to this endpoint to get the character's details
GET /characters/:id

Example Response:

{
  "id": 1,

  "name": "Mr. Cute",

  "image": "https://thumbs.gfycat.com/EquatorialIckyCat-max-1mb.gif",

  "votes": 0
}
When viewing an animal’s details, I should be able to add the number of votes for each animal. This number of votes should then be displayed together with the animal’s details. No persistence is needed for the votes.
## Bonus Deliverables
These bonus deliverables are provided if you want an extra challenge and won't affect score.

## Make sure to commit your work to save your progress before attempting the bonus deliverables!

Add a reset button that resets the votes back to 0
Have a form for adding animals.

## Authors
Gilbert Bageni

## Copyright
Released under the MIT License.md. See the LICENSE file