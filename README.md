# [Grunt](http://gruntjs.com) Plugin for [DocPad](http://docpad.org)

[![Build Status](https://secure.travis-ci.org/RobLoach/docpad-plugin-grunt.png?branch=master)](http://travis-ci.org/RobLoach/docpad-plugin-grunt "Check this project's build status on TravisCI")
[![NPM version](https://badge.fury.io/js/docpad-plugin-grunt.png)](http://badge.fury.io/js/docpad-plugin-grunt "View this project on NPM")
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/RobLoach/docpad-plugin-grunt/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

Run [Grunt](http://gruntjs.com) tasks when building with [DocPad](https://docpad.org).


## Install

```bash
$ npm install --save docpad-plugin-grunt grunt-cli
```

It is required to have `grunt-cli` in *package.json* so that Grunt's command
line interface binary is available to your application.


## Configure

By default, the plugin will run the `default` tasks associated with Grunt when
building with DocPad. This is equivilant to adding the following configuration
to your [DocPad configuration file](http://docpad.org/docs/config):

```coffeescript
  plugins:
    grunt:
      gruntTasks: []
```

The following will run the `"cssmin"` and `"uglify"` tasks from Grunt:

```coffeescript
  plugins:
    grunt:
      gruntTasks: ["cssmin", "uglify"]
```


## History
[You can discover the history inside the `History.md` file](https://github.com/robloach/docpad-plugin-grunt/blob/master/History.md#files)


## Contributing
[You can discover the contributing instructions inside the `Contributing.md` file](https://github.com/robloach/docpad-plugin-grunt/blob/master/Contributing.md#files)


## License
Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/)
<br/>Copyright &copy; 2013 [Rob Loach](http://robloach.net)
