![CoffeeScript](http://coffeescript.org/documentation/images/logo.png)
```
###*
 # @ngdoc controller
 # @name esefpy.web.dashboard.controllers:DashboardExportCtrl
 # @description
 # Export modal window controller for dashboard.
###
angular.module "esefpy.web.dashboard"
  .controller "DashboardExportCtrl", ($scope, $log) ->

    $scope.fieldsCollapsed = true

    return
```

Compiled Javascript
```
/**
 * @ngdoc controller
 * @name esefpy.web.dashboard.controllers:DashboardExportCtrl
 * @description
 * Export modal window controller for dashboard.
 */
(function() {
  angular.module("esefpy.web.dashboard").controller("DashboardExportCtrl", function($scope, $log) {
    $scope.fieldsCollapsed = true;
  });

}).call(this);
```