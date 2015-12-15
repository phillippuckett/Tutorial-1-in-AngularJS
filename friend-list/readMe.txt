###Step 1:
- Create index.html
- create a folder called 'js'
make html with styles.css and make the background a color with a text " "
- link the css on your page

###Step 2:
- Add Angular Reference from angularjs.org
- Create an app.js file and reference it in the HTML, in the js folder
- Create an mainCtrl.js file and reference it in the html, in the js folder

###Step 3:
- Make the module in app.js
- Add ng-app to HTML

###Step 4:
- Make a controller in mainCtrl.js, with the friendsList module we made
    -To get to a module call 
        var app = angular.module('friendsList');
        app.controller(....)
    -Do not use the square brackets when getting a module. Only when making one.
- Add ng-controller in HTML using your mainCtrl
- Add your name to $scope.test in your controller
- double mustache in html to show {{test}}

###Step 5:
- Create friends array in controller on $scope.friends
- ng-repeat to show friends in html