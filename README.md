Just Below the Surface
Project #2 for UCF Coding Boot Camp
Meet the Team
Orlando Robbio, Jeffery Richards, Aaron Mitchell, Shannon Roberts
We created an app that allows users to search movies, games and television shows to find fan theories. These fan theories are written and uploaded by the user. 
Project 2 Requirements:
* GitHub: deployed to 
* Heroku: deployed 
1. Use a Node and Express Web Server; Using node we used a “node init” and ran “npm install express” in the terminal to set up the package-lock.json and package.json. In our server.js we required the packages
2. Be backed by a MySQL Database an ORM; We used Sequelize for the database created which will store all of the fan theory stories written by the users. 
3. Have both GET and POST routes for retrieving and adding new data
4. Be deployed using Heroku (with Data); We successfully deployed the project to Heroku. 
5. Utilize at least one new library, package, or technology that we haven’t used: 
6. Mocha/CHAI (npm install package) Played with this package to see what it can do
7. Materialize (works in conjunction with bootstrap on front-end)
8. Have a polished frontend / UI; We used Bootstrap, CSS to style. We wanted our site to look inviting while displaying an image relative to our app.
Have folder structure that meets MVC Paradigm:
* Models
* * Index.js
* * Post.js
* Node_modules
* Public
* * CSS
* * * Styles.css
* * JS
* * * Blog.js
* * * Cms.js
* * * postData.js
* * blog.html
* * cms.html
* * postData.html
* Routes
* * Html-routes.js
* * Post-api-routes.js
Package-lock.json
Package.json
README.md
Schema.sql
Server.js
1. Meet good quality coding standards (indentation, scoping, naming). We created good clean beautified code and scoped our files using the MVC structure.
2. IF we use an API: Must not expose sensitive API key information on the server, see Protecting-API-Keys-In-Node.md We have a config.js file that holds a secret API key using a dotenv file. Future development: RESTful API usage. (www.restapitutorial.com)    
Config .json file set up for jaws DB 
