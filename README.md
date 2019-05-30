# dragARoom-frontend
Module 3 paired(3 this time round) programming project at Flatiron School London. Drag a room, an app allowing users to drag, drop &amp; arrange furniture in a room and save layouts. Built using JavaScript for the frontend and Ruby on Rails for the backend.

The drag-a-room app was a module 3 project where we decided to experiment with JavaScript as a method of dragging and dropping items on the screen.

Working in a team of 3 and had a week to cover the project through from ideation to MVP.

For the frontend, we initially attempted to write JS code that enabled drag and drop functionality ourselves but quickly realised that it was a larger task than we had time for. At this point we looked at draggable JS libraries and began to test them out. We finally settled on Plain-Draggable as it had good enough documentation for us to deploy it quickly.

For the backend we used rails to persist room designs. The biggest challenge here was isolating the page coordinates of each piece of draggable furniture.

[Example video](https://www.youtube.com/watch?v=xH20BRSwIAM&feature=youtu.be)<br>

## Start-up instructions:

###### backend;<br>
To access the backend, go to the project directory:<br>
`cd server`<br>
Then type:<br>
`rails s`<br>
This will start the rails server on port 3000. You can view the JSON data in your browser[http://localhost:3000]


###### frontend; <br>
To access the frontend, go to the project directory:<br>
Type `open index.html`<br>

## Technologies Used

**Frontend**:<br>
Javascript, HTML & CSS<br>
[PlainDraggable](https://anseki.github.io/plain-draggable/): The simple and high performance library to allow HTML/SVG element to be dragged.<br>

**Backend**:<br>
[Rails API](https://github.com/rails-api/rails-api): Bridge between Frontend & Backend utilising JSON data-file structure for Frontend data access<br>
Ruby<br>
[PostgresSQL](https://www.postgresql.org/): Extends SQL language, SQL is utilized for backend data storage 

