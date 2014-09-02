SpeedTest.JS
============

JavaScript class to test the speed of JavaScript code

##Get started
Once downloaded, include it in your html

```html
<script type="text/javascript" src="path/to/SpeedTest.js"></script>
```

##The Constructor

The SpeedTest class takes three parameters :

1. Function name
2. Function parameter :
  * A single parameter or an array of parameters
3. Number of repetitions (optional, default = 10000)

Examples:

```js
var FunctionNameToTest = new SpeedTest(FunctionName, FunctionParmater);
```
or
```js
var FunctionNameToTest = new SpeedTest(FunctionName, FunctionParmater, 5000);
```
