# SLDRBS

Swinburne Library Discussion Room Booking System

## Requirement

Install [node.js](http://nodejs.org/)

Install [generator-angular](https://github.com/yeoman/generator-angular) with npm from node:
```
npm install -g generator-angular
```

Install [karma](http://karma-runner.github.io/0.8/index.html) with npm from node:
``` 
npm install -g karma
```

Install [generator-karma](https://github.com/yeoman/generator-karma) with npm from node:
```
npm install generator-karma
```


Grunt and Bower package from node.js should be installed along when `generator-angular` and `generator-karma` was installed

Now check out [generator-angular](https://github.com/yeoman/generator-angular) and of course [AngularJS](http://angularjs.org/) itself for more info on how to develop.


## Development and Testing

To start server use grunt
``` 
grunt server
```

To start test server use karma
```
karma start
```

To run end-to-end test use the karma e2e configuration file
```
karma start karma-e2e-conf.js
```

### Happy Hacking!