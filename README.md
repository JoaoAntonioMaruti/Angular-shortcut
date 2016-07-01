# ShortcutJS from AngularJS 1.x.x

#### Version 0.0.1
### How to use
 Add module
```javascript
angular.module('app', ['ngShortcut']);
```
Inject in your controller
```javascript
.controller('YourAwsomeCtrl', function($scope, Shortcut){
    // code
})
```
Use
```javascript
Shortcut.add("Ctrl+Shift+C",function() {
	// code
});
```