# Util.inspect for browsers

Usage: 
```js
UtilInspect(Object, depth = 1);
```

ex)
```js
UtilInspect({'function': new Function()}, 0)
/*
 output is
 {
  function: [Function: anonymous]
 }
*/
```
