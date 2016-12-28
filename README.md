NGSwitchery
===========

An AngularJS Directive for [Switchery](http://abpetkov.github.io/switchery/).

##Usage##

1. Include `switchery/dist/switchery[.min].css` from your vendors/components folder in your links.
2. Include `switchery/dist/switchery[.min].js` from your vendors/components folder in your scripts.
3. Include `ng-switchery.js` in your scripts
4. Declare a dependency on the NgSwitchery module
5. Add the `ui-switch` attribute to a checkbox.
6. ng-model = 'a',a does not express any meaning,you can use any words to express.

##Example##

Declare a dependency on the module
```javascript
angular.module('myModule', ['NgSwitchery']);
```

Insert checkbox html
```html
<input type="checkbox" class="js-switch" ui-switch checked ng-model = 'a'/>
```

Setting Options
```html
<input type="checkbox" class="js-switch" ui-switch="{color: '#E43B11', secondaryColor: '#F89279'}" ng-model = 'a'/>
```

Disable switch
```html
<input type="checkbox" class="js-switch" ui-switch ng-disabled="isDisabled" ng-model = 'a'/>
```


Bower install
```
bower install ng-switchery
```

##Alternative##
You may also wish to look at how to achieve this with [pure CSS](https://github.com/abpetkov/switchery/issues/13).

##Notice on Version##
This project is still in its very early stages and should not be considered production ready.

At this time we are no longer using this project, but will continue to maintain it until someone else agrees to take over. This means that updates will be slow as this is not a priority for us. New releases will be made as our team has time to volunteer to the project.
