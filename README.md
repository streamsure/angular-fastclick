# angular-fastclick

### Update
Another reason to use this wrapper is that the Angular team have deprecated: (since v1.5.0) their implementation and advise all developers to use fastclick this project helps you do just that.

The [ngClick](https://docs.angularjs.org/api/ngTouch/directive/ngClick) directive is now deprecated and disabled by default and the directive will receive no further support and might even be removed from future releases. If you need the directive, you can enable it with the $touchProvider#ngClickOverrideEnabled function.

To learn more about the 300ms delay, this [Telerik](http://developer.telerik.com/featured/300-ms-click-delay-ios-8/) article gives a good overview.

Why does this project even exist? Well it's not in npm and I hate bower and can't be a55ed to raise an issue as ng-fastclick repo has not had any updates in over a year but I use it currently in some hybrid projects so wanted easy access to it via my build pipes.




# ng-fastclick

This is a very thin (3 line!) Angular wrapper around the [FT's](https://github.com/ftlabs) fantastic [FastClick](https://github.com/ftlabs/fastclick)

## Installation

In your Angular project, run `bower install --save ng-fastclick` to save the
module. Then, in your HTML, add:

``` html
<script src="/path/to/bower_components/ng-fastclick/dist/index.min.js"></script>
```

And lastly, in your Angular module, include `ng-fastclick` as a dependency:

``` javascript
angular.module('my-app', ['ng-fastclick'])
```

