# Web2900 - Modern MV* Front End Frameworks (angular)

In this course, students learn the in-depth workings of a modern MV* front end framework (AngularJS or React) and the MV* design pattern in general. They will develop two applications of their own using a modern front-end framework.

Students will be presented with 10-15min formative assessments every single day in order to reinforce their recall of the angular concepts.

##Summary


##Homework


#Lesson Plan
##Day 1
Angular basics, explaining what problem it solves and key terms: module/app, controller, scope, service, directive. 
Do a formative assessment based on terminology and an exercise involving a really simple module with variables bound to the scope and using expressions to dynamically populate a page based on the value of expressions.
Start 50 examples demos and exercises. Example 1 - 10. Demo progression from plain HTML files, through plain js, jquery, backbone and angular. Purpose is to demonstrate what angular is doing behind the scenes for us. Students are asked to create basic examples based on the exercises.
##Day 2
Work through examples 11 - 20.
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
Formative assessment on directive syntax, angular terminology and service/dependency injection syntax. We need to get them to memorize the directive object: restrict, template/templateUrl, scope, link. After that, create another directive for a button which will reload data from the server (the endpoint should deliver something randomized). A discussion on passing variables and functions from the controller $scope to the isolated scopes will be necessary. After the break, discuss ng-repeat directive and have them implement something like a restaurant menu where the menu items are brought in from the controller $scope. This project should make use of the ng-src directive as well.
##Day 4
Formative assessment on directive syntax, expressions, service/dependency injection syntax, filters, and angular terminology. Also, create a service to asynchronously load the food items for the restaurant page from a restful endpoint we provide. Discuss how hardcoding an object might be a good way to start a front end since a REST service can be incorporated so neatly. Then give students a started html template and ask them to hit a restful endpoint and load data about clothing items. Use a service to load the data, inject the service into the main controller, use it to update the $scope, create a directive for each clothing article, and finally use ng-repeat to display all clothing articles from the server.
##Day 5
Formative assessment on directive syntax, expressions, service/dependency injection syntax, filters, and angular terminology. Then introduce Angular Routing and the routeprovider and routeparams services. Students will go through a guided project to implement an angular SPA with at least 2 view templates. Then they will be shown a working version of the sweets complete site, and they will finally be asked to convert the sweets complete site into an angular SPA using routing.
##Day 6
Formative assessment on directive syntax, expressions, service/dependency injection syntax, filters, and angular terminology. Then modify sweetscomplete site so that the candy items asynchronously through a service.
