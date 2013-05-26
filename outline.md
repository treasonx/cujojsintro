
#cujoJS

The architectural toolkit for building highly modular, maintainable web
applications that are easy to test and refactor, with zero framework lockin.

[URL](http://www.cujojs.com)


#What is cujoJS?

* Set of libraries which can be used to build applications
* Not dependent on any one library
* Can be mixed with existing frameworks (Backbone, Angular, etc)


# Meet the pieces of cujoJS

* List names and Icons for each library. 


# curl.js

* A fast AMD modules and resource loader. 

* Sort of like RequireJS o_O

* What problem does it solve?

  Makes it easy to break up a large application into modules. These modules can
  then be built or loaded at runtime. 

##Code Example



# cram.js

* a build tool for AMD and CommonJS modules. 

* Sort of like r.js

* What problem does it solve?

  Takes small AMD modules and assets and bundles them into one file for
  production use. 

## Code Example


# meld.js

* AOP for JavaScript

* Nothing like it that I know of :) 

* What problem does it solve?

  Allows you to easily add behavior to objects without modifying the original
  implementation. Aspects can be shard across more than one object to keep your
  code simple and DRY. 

## Code Example

# when.js

* a fast Promises/A+ implementation with other async goodness

* Q.js

* What problem does it solve?

  Easy management of multiple async callbacks as well as error handling in async
  APIs. 

## Code Example

# msgs.js

* PubSub and more!!!

* Lots of pubsub out there, nothing this full featured. 

* What problem does it solve?

  Manage the complexity of message passing in a javascript application across
  client and server. 

## Code Example

# rest.js

* http client library for the Browser and Node. 

* many clients out there, nothing that I know of unifies client and server API

* What problem does it solve?

  One api for making HTTP request without having to worry about the environment
  you are running in. 

## Code Example

# poly.js

* Set of ES5 shims for JavaScript

* Underscore/LoDash provide similiar functionality without modification of built in
  objects. 

* What Problem does it solve?

  Older browsers do not support some of the nice iterator APIs or other goodness
  that comes with ES5. This library adds support so you dont have to worry about
  it!

## Code Example

