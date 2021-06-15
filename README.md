# Tech-News Python Forum

[Deployed Application](https://technews-python.herokuapp.com/)

Tech-News is a website that allows users to share links to their favorite tech resources, upvote their favorite links, and comment on other people's links. Originally, this website utilized node.js for backend development, but was refactored to utilize Python and Flask instead.

# Inner-Workings of the Website

This website was created by ultizing the following technologies: 
* Python
* Javascript 
* MySQL
* SQLAlchemy
* Gunicorn
* Jinja2
* Bcrypt

# Future Developments
The following are ideas for future changes for the website: 
* Allowing for searchability for posts/topics
* Organizing links into categories 
* Changing from MySQL to Postgresql
* Profile pictures for users
* Utilizing frontend framework, such as AngularJS

# User Stories

**As a user, I want to be able to view the home and dashboard pages in the browser**

* Set up database and models
  * As a user, I need a database that can store my account, posts, comments, or upvotes
* Finalize homepage views with data and filters
  * As a user, I want to be able to see my posts on the homepage
  * I expect to see dates, URLs, and plural words properly formatted
* Implement user logins and sessions
  * As a user, I want to be able to log in and have my session remembered if I refresh the page
* Build and safeguard remaining routes
  * As a logged-in user, I want to be able to create new posts and comments and upvote other posts
* Deploy the app
  * As a user, I want to be able to visit the app on a public URL
