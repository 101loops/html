html [![Build Status](https://secure.travis-ci.org/101loops/html.png)](https://travis-ci.org/101loops/html) [![GoDoc](https://camo.githubusercontent.com/6bae67c5189d085c05271a127da5a4bbb1e8eb2c/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f736d61727479737472656574732f676f636f6e7665793f7374617475732e706e67)](http://godoc.org/github.com/101loops/html)
======

This Go package to load, compose and render HTML templates.


### Features

- fluent API for building template sets
- auto-reloading of templates on rendering
- caching of parsed template trees
- allow redefinition of existing templates
- validate template completeness at time of creation not rendering
- various helper functions (e.g. runTemplate to execute template dynamically) 


### ToDos
 
- render any error to HTML (+ display snippet of template source)
- allow custom template parser


### Installation
`go get github.com/101loops/html`

### Documentation
[godoc.org](http://godoc.org/github.com/101loops/html)

### License
MIT (see LICENSE).