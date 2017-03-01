# angular-fastclick


Why does this project even exist? Well [ng-fastclick](https://github.com/8bitDesigner/ng-fastclick) is only available in bower and not in npm and I really hate having to use bower and I also can't be a55ed to raise an issue as ng-fastclick repo has not had any updates in 24 Months.  

I do use fastclick currently in some of my hybrid mobile projects as it's really quite performance orientated, I also wanted easy access to it via my build pipes so I added it to npm for everyone to use as well, enjoy!

``` javascript
$ npm i angular-fastclick --save
```

``` javascript
angular.module('your-app', ['ng-fastclick'])
```


#### Update
Another reason to use this wrapper is that the Angular team have deprecated: (since v1.5.0) their implementation of the 300ms delay and advise all developers to use fastclick and this project helps you do just that.

The [ngClick](https://docs.angularjs.org/api/ngTouch/directive/ngClick) directive is now deprecated and disabled by default and the directive will receive no further support and might even be removed from future releases. If you need the directive, you can enable it with the $touchProvider#ngClickOverrideEnabled function.

To learn more about the 300ms delay, this [Telerik](http://developer.telerik.com/featured/300-ms-click-delay-ios-8/) article gives a good overview.


