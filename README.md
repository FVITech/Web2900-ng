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
1. create-react-app overview
2. JSX
3. Component Composition
4. Tweeter example
5. Exercises

##Day 3
1. Props
2. Communicating with parent components
3. PropTypes
4. Tweeter example with PropTypes
5. Exercises


##Day 4
1. Children
2. Children types
3. PropTypes for children
4. Comparison with Transclusion in Angular
5. A more elaborate example
6. Exercises


##Day 5
1. Key props
2. Github example
3. Exercises

##Day 6
1. State
2. Counter example
3. setState as Asynchronous.
4. Different forms of setState
5. Shallow vs Deep Merge
6. Handling events
7. What to put in state

##Day 7
1. Thinking declaratively
2. Where to keep state
3. Component types
4. Example - Shopping site
5. Exercises

##Day 8
1. Controlled vs Uncontrolled inputs
2. Component lifecycle
3. Example shopping site - completion
4. Exercises
5. Mid-term

##Day 9




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
