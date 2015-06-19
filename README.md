# ng-model
This module has the function to collect objects from view, facilitating the bind-to-bind

In many cases AngularJs loses the reference element due to the dynamic loading of components of the screen, all this module is able to retrieve or set the data these objects.

## Bower install de dependency
```
$ bower install ng.model --save
```

## HTML dependency
```
<script src="bower_components/ng-model/dist/ng-model-1.0.1.min.js"></script>
```

## Module AngularJS include
```
angular.module('example', ["ng.model"]);

angular.module('example').controller('MainCtrl', function ($scope, $model) {
  $model.get('test');
  $model.set('test', '...');
});
```
