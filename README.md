# Web2900 - Modern MV* Front End Frameworks (angular)

In this course, students learn the in-depth workings of a modern MV* front end framework (AngularJS or React) and the MV* design pattern in general. They will develop two applications of their own using a modern front-end framework.

Students will be presented with 10-15min formative assessments every single day in order to reinforce their recall of the angular concepts.

##Summary


##Homework


#Lesson Plan
##Day 1
Angular basics, explaining what problem it solves and key terms: module/app, controller, scope, service, directive.
Do a formative assessment based on terminology and an exercise involving a really simple module with variables bound to the scope and using expressions to dynamically populate a page based on the value of expressions.
##Day 2
Another formative assessment on terminology, students will create a service under instructor guidance. The service will make a restful call and be injected into the controller to populate the controller scope. Build some kind of application analogous to the quote of the day app, using view expressions and filters (uppercase). After the break, introduce element directives. Refactor the quote of the day app so it uses a directive for the quote display.
##Day 3
Formative assessment on directive syntax, angular terminology and service/dependency injection syntax. We need to get them to memorize the directive object: restrict, template/templateUrl, scope, link. After that, create another directive for a button which will reload data from the server (the endpoint should deliver something randomized). A discussion on passing variables and functions from the controller $scope to the isolated scopes will be necessary. After the break, discuss ng-repeat directive and have them implement something like a restaurant menu where the menu items are brought in from the controller $scope. This project should make use of the ng-src directive as well.
##Day 4
Formative assessment on directive syntax, expressions, service/dependency injection syntax, and angular terminology. Also, create a service to asynchronously load the food items for the restaurant page from a restful endpoint we provide. Discuss how hardcoding an object might be a good way to start a front end since a REST service can be incorporated so neatly. Then give students a started html template and ask them to hit a restful endpoint and load data about clothing items. Use a service to load the data, inject the service into the main controller, use it to update the $scope, create a directive for each clothing article, and finally use ng-repeat to display all clothing articles from the server.
##Day 5
Formative assessment on directive syntax, expressions, service/dependency injection syntax, and angular terminology. Then introduce Angular Routing and the routeprovider and routeparams services. Students will go through a guided project to implement an angular SPA with at least 2 view templates. Then they will be shown a working version of the sweets complete site, and they will finally be asked to convert the sweets complete site into an angular SPA using routing.
##Day 6
Load the sweetscomplete items asynchronously through a service.
