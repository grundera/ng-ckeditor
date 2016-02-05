CKEditor + AngularJS
====================
[![Build Status](https://travis-ci.org/grundera/ng-ckeditor.png)](https://travis-ci.org/grundera/ng-ckeditor) [![Coverage Status](https://coveralls.io/repos/grundera/ng-ckeditor/badge.png)](https://coveralls.io/r/grundera/ng-ckeditor)


Code licensed under New BSD License.

## Installing via Bower
```
bower install ng-ckeditor
```

##Usage
```html
<textarea ckeditor="editorOptions" ng-model="modelName"></textarea>
```

```js
// add dependency
angular.module('app', ['ngCkeditor'])

// setup editor options
$scope.editorOptions = {
    language: 'ru',
    uiColor: '#000000'
};
```
