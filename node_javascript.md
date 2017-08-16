# ![Elevator Up](http://elevatorup.com/img/eulogo-87259dc5.png)  Node / ECMAscript(JavaScript) Development Guide

1. [Common Packages](#common-packages)
2. [ECMAscript Style Guide](#javascript-style-guide)
3. [Eslint](#eslint)
4. [ES6 tricks](#es6-tricks)

### Common Packages
In order to try and keep a consistency between projects, this is a list of some of our preferred gems. This is by no means a definitive list, just what we prefer to use for certain situations.

| package | purpose |
| --- | --- |
| [underscore](underscorejs.org) | A utility library for doing common, useful things. (loops, finding, parsing, etc.). |
| [express](https://expressjs.com/) | Web traffic management. |
| [morgan](https://github.com/expressjs/morgan) | Web traffic logging. |
| [opBeat](https://opbeat.com/nodejs/) | Track request speeds and traffic data. |
| [dotEnv](https://github.com/motdotla/dotenv) | Support for `.env` files to store sensitive information with a project. |
| [mustache](https://github.com/janl/mustache.js) | A templating library. |
| [chai](http://chaijs.com/) | A helpful test assertion library |
| [mocha](https://mochajs.org/) | A test runner for simple **feature testing** |
| [cucumberjs](https://github.com/cucumber/cucumber-js) | A **gherkin** test runner for **behavior driven testing**. |

### ECMAscript Style Guide
We are currently using the default [ECMAscript Style Guide](https://github.com/airbnb/javascript) supplied by [Airbnb](http://airbnb.io/).
As we move forward, we may fork this style guide and update it to match our coding style.

### Eslint
A template for our eslint config can be found [here](templates/javascript/eslint.js).

### ES6 tricks
In order to keep code modular we encourage the use of [ES6 promises](http://www.datchley.name/es6-promises/).  Modules that are promises are easier to chain and test.

For Example:
```javascript
// Some module
module.exports = (options = {}) => {
  const name      = options.name;
  
  return new Promise((resolve, reject) => {
    if(!name) reject(new Error(`This module needs a name!`));
    
    resolve(`This module is named, ${name}`);
  });
};
```