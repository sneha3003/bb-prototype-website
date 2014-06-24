# bb-prototype-website

> Front-end website prototype template.

## Using the template

First things first, install [Node.js](http://nodejs.org).

Then use npm to install [Grunt](http://gruntjs.com/)

```
$ npm install -g grunt 
```

Then, once you have the project downloaded, run the command `npm install && bower install` in the root of the project to install all dependencies.

Once this finishes running, you can build the project by running the command `grunt`

[TODO: Loads more documentation]

Do not edit files in the grunt generated __/dist__ directory (these will always be deleted).

## Adding packages
When you install any new npm packages use the command:
`npm install <package> --save-dev`

When you install any new Bower packages use the command:
`bower install <package> --save-dev`
Notes:

 * Add new frameworks/libraries as _dev_ dependencies as they get compiled and moved for production during the build process
 * Remember to keep packages updated as needed
 * However, do not update jQuery to 2.x unless you are dropping support for Internet Explorer 6, 7, and 8

You can also use our Yeoman generator
[TODO: Actually build the generator]

### What is [Grunt.js](http://gruntjs.com/)?

In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it, a task runner can do most of that mundane work for you—and your team—with basically zero effort.

[Find out more at the Grunt.js website](http://gruntjs.com/).

### What is [Assemble](http://assemble.io/)?

Assemble is a component and static site generator that makes it dead simple to build modular sites, documentation and components from reusable templates and data.

* [Documentation](http://assemble.io/docs) 
* [Plugins](http://assemble.io/plugins) - Plugins extend the core functionality of Assemble.
* [Helpers](http://assemble.io/helpers) - Documentation for the helpers in the [handlebars-helpers](http://github.com/assemble/handlebars-helpers) library.

### What is [Bower](http://bower.io)?
Bower is a package manager for the web. It offers a generic, unopinionated solution to the problem of __front-end package management__, while exposing the package dependency model via an API that can be consumed by a more opinionated build stack.

## Release History
 * 2014-06-24	v0.6.0 	Added Bower to automate front-end package management
 * 2014-06-13   v0.5.0
 * 2014-02-28   v0.4.0
 	* Split grunt tasks for quicker 'watch'
 	* Extra layouts using 'extend, content, block' method
 	* Other minor fixes
 * 2014-02-28   v0.3.0   Massive update (too much to list, see commit log)
 * 2014-02-17   v0.2.0   Render components list
 * 2014-02-13   v0.1.0   Inital project upload
