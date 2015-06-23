underscore-ng
=============

Underscore.js factory for AngularJS

## Installation

`bower install underscore-ng --save`

## Usage

```js
var app = angular.module('app', ['underscore']);

app.controller('Controller', ['_', function($scope, _) {
  $scope.first = _.first([5, 4, 3, 2, 1]);
}]);

```
