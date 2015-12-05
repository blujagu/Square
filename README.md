# Square[JS]

## Installation
  npm install squarejs --save
  or download the zip

  SquareJS can be run:
  * minified using script src="lib/square.min.js"
    See "examples/Demo_Buttons" for a sample implementation
  * unminified using script src="lib/square.js"
  * as a require.js module, in which case you don't use square.js
    For require, use only the files under "lib/modules"
    See "examples/Demo_Buttons_Require" for a sample implementation
==================================
## Modern Application Development using:
* square.js - Provides requisite low-level functionality and shims for the rest of the framework.
* box.js - It's a view in a box, just pass it a 'box config' and you get back a view with all your eventing hooked up. Sweet!
* eventHub.js - Provides native JavaScript Events to data models for data-binding without loops or synthetic events.
* notify.js - Experimental router and pub/sub module still under heavy development.
* request.js - Promise wrapped AJAX requests for when you need to get stuff.
* lobro.js - Persist data to localStorage.
* temple.js - Lightweight templating engine that lets you write valid html templates and automate event management.

## SquareJS contains SquareDB ./lib/modules/squaredb/ or included in square.js and square.min.js
* squaredb.js - Unique and super fast relational database model on the client. Provides SQLish syntax and tons of cool features.
* aggregates.js - Mathematical functions for column data: sum, max, min, avg, count
* comparator.js - Handles comparison logic for WHERE statements
* go.js - Does the heavy lifting for all queries as it takes the QueryObject and executes the query.
* Select.js - Creates instances of the SELECT statement providing FROM and WHERE.

## Online Demo
http://squaredb.com/examples/demo1/index.html

## This framework is in the 'BETA' stage of development
Current version 1.0.0

## Updates
### 11/29/2015
Squobs was dropped, Square.js now actually contains the framework, and there's a minified Square available which is super tiny and crazy fast.
Also, today marks the first official beta version; we are no longer in alpha development which means lots of stabilization, hardening, and documentation in the coming weeks.

### See changelog for all previous updates.
