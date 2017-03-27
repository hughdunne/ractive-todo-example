# ractive-todo-example

This is a sample project I created for a talk at the Phoenix Javascript meetup on March 29, 2017.

You can follow along by cloning this project, then checking out the following versions in sequence:

#### Initial version
```sh
git checkout v1
```
Pure HTML, no Javascript.

#### Using Handlebar templates
```sh
git checkout v2
```
Illustrates one-way binding. We can update the model, refresh the page and the view will update.

#### Using Ractive MVC
```sh
git checkout v3a
```
Two-way binding. Dynamic updating of model and view.

#### Ractive with computed properties
```sh
git checkout v3b
```
A minor refinement. Use computed properties to simplify code and avoid duplication.

## Other resouces

* [Ractive home page](http://www.ractivejs.org/) - Includes examples, tutorials and reference documents.
* [Color picker and RGB-HSL converter](https://jsfiddle.net/fiddlersgreen/ycx3rkyx/show) - Illustrates using Ractive observers. (Source code is [here](https://jsfiddle.net/fiddlersgreen/ycx3rkyx).)
