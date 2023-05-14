# CS465-Fullstack
CS 465 Full Stack Development with MEAN

# Architecture
- Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Express HTML
-Is written in Javascript.
-Allows the rendering of HTML pages dynamically.
-Includes various middleware modules which you can use to perform additional tasks on request and response.

Javascript
-JavaScript is an interpreted, lightweight programming language it is incredibly simple to use. It's free to use and cross-platform.
-Reduces the time required by other programming languages like Java for compilation.
-Can be used in game creation, mobile app development, and desktop app development

Single-page application
-An SPA (Single-page application) is a web app implementation that loads only a single web document, and then updates the body content of that single document via JavaScript APIs such as XMLHttpRequest and Fetch when different content is to be shown.
-To execute a user’s request, an SPA loads a small JSON file instead of a new web page.
-Asynchronous requests, when done right, can reduce server load and require less bandwidth.

- Why did the backend use a NoSQL MongoDB database?

MongoDB database was utitlized for this project because of its ablity to scale horizontally and because it allows for easy updates to schemas.

# Functionality
- How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

In this project JSON is used to store and display data. JSON is a text-based way of representing JavaScript object literals, arrays, and scalar data. Javascript on the other hand is a scripting lanuage that allows for the creation of dynamic web page content. JSON allows for Javascript objects to be sent to and stored on the backend. Once the data is stored the front end can request that the data be pulled and used from the backend.

- Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

One instance in the full stack development process where I had to refractor code to improve functionality was changing the code from a simple webpage to a Single page application. Some benefits of reusable user interface components are a decrease in errors, provided the components are throughly tested and perfected, saves time and resources during development and reduces the overall size of the applicaion.

# Testing
- Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.  

When developing this application API unit testing was needed to ensure that each endpoint was a correct response based on the  given request. One way that this testing was done was by sending a request to MongoDB to get and display the trip details on the website.

- Explain your understanding of methods, endpoints, and security in a full stack application. 

Methods ensure the functionality and dynamics of a web page. Methods can be used to retrieve or modify a database so that a specific functionality can be implemented. Some examples of methods are the GET, POST and PUT methods. They use database functions to modify the database according to what the user requires. An endpoint is a remote computing device that communicates back and forth with a network to which it is connected. 

# Reflection
- How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has really opended my eyes to all the inner workings of a full-stack application. It has given me a better understanding of the types of projects and applications that I will be working on in the professional field. I was able to gain new skills in ExpressJS, Angular and nodeJs. To my understanding these are very valuable and sought after skills to have in the coding industry and I am very excited to be able to build more on these skills. I was also able to see first hand how the application all came together from start to finish and I believe this knowledge and understanding will be very valuable in my future career field.
