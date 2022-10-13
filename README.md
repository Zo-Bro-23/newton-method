# Newton-Method
This is a simple package demonstrating the Newton Method for finding roots of a function. [Learn more](https://en.wikipedia.org/wiki/Newton%27s_method).
```js
const newtonMethod = require('newton-method')

console.log(newtonMethod('x^2', 100, 5))
```

### **```newtonMethod(func, inputIterations, inputInitial)```**

#### func - ```Required``` - Function to evaluate - Uses ```mathjs``` formatting - See [here](https://mathjs.org/docs/expressions/syntax.html) for more information

#### inputIterations - ```Default: 100``` - Number of times to iterate Newton's Method - More times yields more accurate results

#### inputInitial - ```Default: 0``` - Initial value to start applying Newton's Method to

## Result
```js
3.944304526105059e-30
```