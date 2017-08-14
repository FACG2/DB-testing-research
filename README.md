# DB-testing-research

### List of JavaScript / Node.js tools for testing a database & example:

Databases are the core of any application ,and it may be cruical for any product if it's not relaiable,So we create tests to test our Databases to insure it's relaiabilty and quality before deploying it to the costumers.
So doing test for the database is great and prevent your aplication from crashing.
There is alot of Node.js tools for testing DB's:

**1. pgtest :**  
  node-postgres-test is a module that provides easy unit testing for the popular node-postgres.

   How to install :``` npm install pgtest ```

**2. Chai :**  
Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.

### What is mock and how to use it?
Mock is a method/object that simulates the behavior of a real method/object in controlled ways. Mock objects are used in unit testing.

Often a method under a test calls other external services or methods within it. These are called dependencies. Once mocked, the dependencies behave the way we defined them.

With the dependencies being controlled by mocks, we can easily test the behavior of the method that we coded. This is Unit testing.

So, In general it's much easier to test database when it's mocked.

#### Mocha Demonstration:
  Example:
##### GETTING STARTED:
```$ npm install mocha```

```$ mkdir test```

open text editor ```atom .```

write the following code:
```
var assert = require('assert');
describe('Array', function() {
  describe('#indexOf()', function() {
    it('should return -1 when the value is not present', function() {
      assert.equal(-1, [1,2,3].indexOf(4));
    });
  });
});
```
**back to your terminal**
```npm test```



<-------------Code Example ---------------->
