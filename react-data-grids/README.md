# React Data Grid 


Installation
------------

```sh
npm install react-data-grid
```

This library is written with CommonJS modules. If you are using
browserify, webpack, or similar, you can consume it like anything else
installed from npm.

Overview 
--------
ReactDataGrid is an advanced JavaScript spreadsheet-like grid component built using React

Themes
------
We use [Bootstrap](https://github.com/twbs/bootstrap). If you want your Grid to get the "default" styling like the picture above, you'll need to include it separately.

```
npm install bootstrap
```
and then import the css from the dist folder when bootstrapping your application
```
import 'bootstrap/dist/css/bootstrap.css';
```

Migrations
--------
If you intend to do a major release update for you react-data-grid check [the migration documents](migrations).
  
Features
--------

- Lightning fast virtual rendering
- [Can render hundreds of thousands of rows with no lag](http://adazzle.github.io/react-data-grid/examples.html#/one-million-rows)
- Keyboard navigation
- [Fully editable grid](http://adazzle.github.io/react-data-grid/examples.html#/editable)
- [Rich cell editors like autocomplete, checkbox and dropdown editors, complete with keyboard navigation](http://adazzle.github.io/react-data-grid/examples.html#/built-in-editors)
- Custom cell Editors - Easily create your own
- [Custom cell Formatters](http://adazzle.github.io/react-data-grid/examples.html#/custom-formatters)
- [Frozen columns](http://adazzle.github.io/react-data-grid/examples.html#/fixed-cols)
- [Resizable columns](http://adazzle.github.io/react-data-grid/examples.html#/resizable-cols)
- [Sorting](http://adazzle.github.io/react-data-grid/examples.html#/sortable-cols) 
- [Filtering](http://adazzle.github.io/react-data-grid/examples.html#/filterable-sortable-grid) 
- [Context Menu](http://adazzle.github.io/react-data-grid/examples.html#/context-menu)
- Copy and Paste values into other cells
- [Multiple cell updates using cell dragdown](http://adazzle.github.io/react-data-grid/examples.html#/cell-drag-down)
- [Association of events of individual columns](http://adazzle.github.io/react-data-grid/examples.html#/column-events)


