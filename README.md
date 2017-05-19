# svg-icons-spin

Group of svg spinner in one file. Possible to use with WebIcon https://github.com/icons8/webicon

Basic usage
---------------
Install bower package:
```bash
bower install --save svg-icons-spin
bower install webicon --save
```

List of icon ID
----------------
* half
* point
* quarter
* line-1
* line-2
* line-3
* line-4
* line-5


Example
--------

```html
<webicon icon="spinner:half"></webicon>
<span webicon="spinner:line-1"></span>
<div data-webicon="spinner:point" alt="point"></div>
```

```javascript
angular.module('app', ['webicon'])
  .config(function($webiconProvider) {
    $webiconProvider
      .svgSet('spinner', 'bower_components/svg-icons-spin/dist/icons-spin.min.svg')
  });
```



