# How to install

npm i number-generator-random-npm

# How to use number-generator-random-npm?

One of the function of this npm is:
```js
generarNumeroAleatorio(min, max) //This function returns a random integer between min and max (inclusive).
```

## What means min and max?

The parameters "min" and "max" are numbers. They represent the range in which the generated number will be placed. The generated number can be any value. Min is the minimun number and max must be the maximun number to be randomized.

### Example:

```js

const numberGenerator = require('number-generator-random-npm');
const generatedNumber = numberGenerator(10, 25); 

console.log(generatedNumber) // Return a random number between 10 and 25.

```

https://placehold.it/150/ffffff/ff0000?text=hello
