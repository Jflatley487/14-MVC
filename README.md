# Tech Blog

This is a CMS-style blog site where developers can publish their blog posts and comment on other developers' posts. The site follows the Model-View-Controller (MVC) architectural pattern and utilizes Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication. It is designed to resemble a Wordpress site and is deployed on Heroku.

## Functionality

The Tech Blog application provides the following features:

- User registration and login: Developers can create an account by signing up with a unique username and password. They can then log in to the site using their credentials.
- Homepage: Upon visiting the site, users are presented with the homepage, which displays existing blog posts, if any have been posted. They can navigate to the homepage by clicking on the homepage option.
- Navigation: The navigation bar provides links to the homepage, dashboard, and log out option. Users can easily switch between different sections of the site.
- Commenting: Users can leave comments on blog posts. When viewing a post, they have the option to enter their comment and submit it. The comment is then saved and displayed along with the username and the date it was created.
- Dashboard: The dashboard is accessible to logged-in users and displays their own blog posts. They can view, edit, or delete their posts from the dashboard. The option to add a new blog post is also available.
- User session management: If a user is idle on the site for a set time, they are prompted to log in again before performing actions like adding, updating, or deleting posts.

## Technologies Used

The Tech Blog application utilizes the following technologies:

- Front-end:
  - HTML
  - CSS
  - JavaScript
  - Handlebars.js (templating language)
- Back-end:
  - Node.js
  - Express.js (web application framework)
  - Sequelize (ORM)
  - MySQL (database)
  - express-session and connect-session-sequelize (authentication and session management)
  - bcrypt (password hashing)
  - dotenv (environment variables)
- Deployment:
  - Heroku (cloud platform)

## Screenshots

![screenshot1]

![screenshot2]

![screenshot3]

![screenshot4]

## License
The Tech Blog application is licensed under the MIT License.
