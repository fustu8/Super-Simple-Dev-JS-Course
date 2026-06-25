# Notes for the Course

Calculations with floats are inaccurate sometimes
so it is always better to use this method.

```javascript
// bad practice
console.log(20.95 + 7.99) // output = 28.939999999999998

// best practice
console.log((2095 + 799) / 100) // output = 28.94

// another example 
Math.round((2095 + 799) * 0.1) / 100
```

automatic type conversion
