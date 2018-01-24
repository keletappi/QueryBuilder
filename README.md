# QueryBuilder
j2objc compilable version of [jQuery QueryBuilder](https://github.com/mistic100/jQuery-QueryBuilder) parser + SQL query builder.
    
[![jQuery QueryBuilder](screenshot.png)](http://querybuilder.js.org/index.html)

---------------------------------------
#### How to compile?
1. have Maven & Java (1.7+) on your system
1. [install j2objc](https://developers.google.com/j2objc/guides/getting-started)
1. `mvn install j2objc:convert -DJ2OBJC_DISTRIBUTION=<path_to_j2objc>`

Check out the [original repository](https://github.com/itfsw/QueryBuilder) for details on how to use the lib to convert the QueryBuilder into SQL. 

Code for creating MongoDB queries was removed due to not wanting to include MongoDB in the cross-compiled result and not needing it for my use case.

