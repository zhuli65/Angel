<!doctype html>
<html lang="en" ng-app="phonecatApp">
  <head>
    <meta charset="utf-8">
    <title>Google Phone Gallery</title>
    <link rel="stylesheet" href="bootstrap.css" />
    <link rel="stylesheet" href="app.css" />
    <script src="angular.js"></script>
    <script src="app.js"></script>
  </head>
  <body ng-controller="PhoneListController">

    <ul class="ul-box">
      <li ng-repeat="phone in phones">
        <span>{{phone.name}}</span>
        <p>{{phone.snippet}}</p>
      </li>
    </ul>

  </body>
</html>
