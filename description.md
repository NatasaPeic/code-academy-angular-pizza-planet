Pizza Planet wants to create an AngularJS app for their restaurant's menu. Here's what it looks like. The menu displays the restaurant's appetizers, mains, and extras.
Mark the tasks as complete by checking them off
1.
Create a new module named PizzaPlanetApp in js/app.js, and then attach it to the <body> element in the view.
2.
Modify the controller:

There is currently a property called $scope.appetizers containing an array of two objects. Add a third object with the following values:
Name: Bruschetta
Description: Grilled bread garlic, tomatoes, olive oil.
Price: 4.95
Attach the controller to the <div class="main"> element.
3.
Display the data in the view:

Inside <div class="appetizer row">, use ng-repeat to loop through the appetizers array. Display each appetizer's name, description, and price using expressions.
Use the currency filter to format an appetizer's price.
4.
View the result by visiting http://localhost:8000 in the browser.
5.
In the controller, add another property called $scope.mains containing an array of three objects. Feel free to use your favorite foods.
6.
In the view, adapt the <div class="appetizer row"> element to create a <div class="mains row"> element. Loop through the mains and display each item using expressions and filters. View the result in the browser.
7.
In the controller, add another property called $scope.extras containing an array of three objects. Feel free to use your favorite sides.
8.
In the view, loop through the extras and display each item. View the result in the browser.
