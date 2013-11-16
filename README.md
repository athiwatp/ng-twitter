ng-twitter [![NPM version](https://badge.fury.io/js/ng-twitter.png)](http://badge.fury.io/js/ng-twitter) [![Build Status](https://travis-ci.org/darul75/ng-twitter.png?branch=master)](https://travis-ci.org/darul75/ng-twitter)
=====================

<<<<<<< HEAD
Angular directive tweets display.
=======
Angular directive for JSON pretty display output, indent and colorized.

Idea was given by the need to display some configuration JSON format files in a back office.

Inspired by this from stackoverflow
[pretty json javascript](http://stackoverflow.com/questions/4810841/json-pretty-print-using-javascript)
>>>>>>> 5b15f5daf533923bfe5e6f280fcdad33010e98b3

Demo
------------
http://darul75.github.io/ng-twitter/


Screenshot
------------

Installation
------------

Using npm:

```
npm install ng-twitter
```

How to use it
-------------

You should already have script required for Angular

```html
<script type="text/javascript" src="angular.min.js"></script>
```

to the list above, you should add:

```html
<link rel="stylesheet" type="text/css" href="ng-twitter.min.css">
```

```html
<<<<<<< HEAD
<script type="text/javascript" src="ng-twitter.min.js"></script>

Then, inject `ngTwitter` in your application module:

```javascript
angular.module('myApp', ['ngTwitter']);
```

<<<<<<< HEAD
and then just add an `div` with `pretty-json` directive name attribute and `json` scope variable attribute.

```html
<div tweets key="authKey" hashtag="hashtag" button="true" count="15" refresh="60"/>
```

`authKey` is your scope authentication key variable.

```javascript
$scope.authKey = 'bzJZSlN4ZnJUYWhyeXdub2R4MzJBOkFHSmw5MnJIeEFTRkpYVW9BSm8zMEpTQzU2Wm0zNFZxZmFVZFh1TUZWamc=';
$scope.hashtag = 'football';
=======
and then just add an `pre` with `pretty-json` directive name attribute and `jsonObj` scope variable attribute.

```html
<pre json='jsonObj' pretty-json />
```

`jsonObj` is your scope json variable.

```javascript
var obj = {a:1, 'b':'foo', c:[false,null, {d:{e:1.3e5}}]};
```

### Attribute

* `key`: scope json variable object
* `key`: scope json variable object
* `key`: scope json variable object
* `key`: scope json variable object
* `key`: scope json variable object

Example with all above features:

```html
<<<<<<< HEAD
<div ng-app="myApp" ng-controller="ctrl">
	<div tweets key="authKey" hashtag="hashtag" button="true" count="5" refresh="10"/>		
=======
<div ng-app='myApp' ng-controller='ctrl'>
  <pre json='jsonObj' pretty-json />
>>>>>>> 5b15f5daf533923bfe5e6f280fcdad33010e98b3
</div>
```

### Build

You can run the tests by running

```
npm install
```
or
```
npm test
```

assuming you already have `grunt` installed, otherwise you also need to do:

```
npm install -g grunt-cli
```

## License

The MIT License (MIT)

Copyright (c) 2013 Julien Valéry

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.




