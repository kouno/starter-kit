##Starter Kit

This contains all libraries that I would expect to have access to when doing some proof of concept (JS/CSS).

* Bootstrap (and jQuery since it's a dependency)
* Sass and CoffeeScript
* Foreman to compile files using watch
* TODO: Add Jasmine for testing

## Install

```
> bundler install
> bower install
```

## Compile coffee and sass files

Add a Procfile with something like:

```
sass-compiler: sass --watch css/input.scss:css/output.css
coffee-compiler: bower_components/coffee-script/bin/coffee --watch --compile js/input.coffee
```
