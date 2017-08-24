# Web2900 - Modern MV* Front End Frameworks (React.js)

In this course, students learn the in-depth workings of a modern MV* front end framework (React) and the MV* design pattern in general. They will develop two applications of their own using a modern front-end framework.

Students will be presented with 10-15 min formative assessments every single day in order to reinforce their recall of React.js concepts.

##Summary

##Homework


#Lesson Plan
##Day 1
Introduction to React, and Front End Frameworks and Libraries. Intro to React basics, explaining what problem it solves and key terms. What are components, and how do you think in components.

 Demo progression from plain HTML files, through plain js, jquery, backbone, angular to a basic "Hello World" React component. Purpose is to demonstrate what makes React so powerful, and to teach the most bare bone React application possible. Students are asked to create basic examples based on the exercises. This will be done with no tooling set-up, using CDN and single HTML page.

 - npm i -g yarn
 - yarn init -y
 - yarn add react
 - yarn add react-dom
 ```
 <!DOCTYPE html>
 <html lang="en">
 <head>
   <meta charset="UTF-8">
   <title>First React Component</title>
 </head>
 <body>
   <div id="app"></div>
   <script src="node_modules/react/dist/react.js"></script>
   <script src="node_modules/react-dom/dist/react-dom.js"></script>
   <script>
     var div = React.DOM.div
     var h1 = React.DOM.h1

     var MyFirstComponent = (
       div(null,
         h1(null, 'This is my first component!')
       )
     )

     ReactDOM.render(MyFirstComponent, document.getElementById('app'))
   </script>
 </body>
 </html>
 ```
- Explain createElement(), virtual DOM and how React does its magic.

##Day 2
Work through lessons 11 - 20.
 - Intialize model using Angular controller
 - Changing scope values asynchronously (use of .apply()).
 - Looping over lists using ng-repeat. Built in directives
 - Basic use of forms and ng-submit
 - Clearing input boxes using data binding
 - Use of ng-click
 - Object enumeration - countries and their populations
 - Building a table
 - Fetching JSON


##Day 3
Work through lessons 21 - 30.
- Dependency Injection syntax & minification issues
- Adding search using angular filters
- Sorting in ng-repeat using orderBy
- Interactive sorting of table columns
- Reverse sorting
- Adding images (country flag). Use of src vs ng-src.
- Add capital and GDP data


##Day 4
Lessons 31 - 40
- Using filters: formatting currency
- Using angular filters in templates
- Preparing for routing
- Using ngRoute, the path to ui-router
- Moving templates for routes into separate files
- Use of parameters in routes
- Using links with routes to navigate between views
- Looking up details for a single country
- Surfacing data on the country details page
- Creating a service(Factory) to load data


##Day 5
Lessons 41 - 50
- Extract country details query into a factory
- Caching in angular
- Caching data in a factory
- Custom filters: create a URI encoder
- RESTful services in angular
- Introduction to custom directives
- Custom directives and controllers
- Fetching data withing custom directives
- Extracting controllers into separate module
- Extracting factories and directives to separate modules using method chaining.


##Day 6
Cat phone tutorial - Emphasize modular approach to building angular 1.5.x angular applications
-- Quiz covering Days 1 - 5


##Day 7
PhoneCat tutorial - Emphasize modular approach to building angular 1.5.x angular applications


##Day 8
Build a Tabs Directive project
https://thinkster.io/angular-tabs-directive


##Day 9
Build an angular project from scratch. Students are asked to choose a project and create it from scratch using their knowledge of angular. The professor offers guidance and support, but it is the student that drives the project. If the student can't come up with an idea, the professor can suggest ideas to the student. As the student progresses in the class, the student is expected to add to the project. Project is due final day of class.



##Day 10
Creating a SPA from a set of HTML pages. The sweets complete application is used to create a SPA. The technique to do so is demonstrated taught to the students, and then the students are challenged to do the same on another set of HTML pages of the students choosing.
- Quiz covering Days 6 - 10


##Day 11
Quiz covering Days 6 - 10
Authentication and authorization with angular
https://thinkster.io/angularjs-jwt-auth
http://jasonwatmore.com/post/2016/04/05/angularjs-jwt-authentication-example-tutorial
http://brewhouse.io/blog/2014/12/09/authentication-made-simple-in-single-page-angularjs-applications.html


##Day 12
Authentication and authorization completed
- Final exam comprehensive
- Final project due
