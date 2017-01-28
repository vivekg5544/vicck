<!DOCTYPE html>
<html ng-app="test">
<head>
  <title>Test Project</title>
  <script type="text/javascript" src="js/angular.min.js"></script>
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
</head>
<script type="text/javascript">
var test = angular.module("test",[]);
 test.controller("testCtrl", function($scope){
     $scope.firstname = "vivek ";
     $scope.lastname = "gupta";
     $scope.mobileno = "8602848510";
     $scope.age = "27";
 });

</script>
<body ng-controller="testCtrl">
<table class="table">
<div> 
  <tr>
    <th>firstname</th>
    <th>lastname</th>
    <th>mobile.no</th>
    <th>age</th>
  </tr>
</div>
<div> 
  <tr>
    <td>{{firstname}}</td>
    <td>{{lastname}}</td>
    <td>{{mobileno}}</td>
    <td>{{age}}</td>
  </tr>
</div>
</table>

</body>
</html>
