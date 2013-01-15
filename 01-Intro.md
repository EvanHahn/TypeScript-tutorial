_This tutorial is intended for people that are familiar with some more advanced JavaScript. You either know how to install things with [npm](https://npmjs.org/) or are willing to learn._

What is TypeScript?
===================

In short, TypeScript is JavaScript with more features.

JavaScript is very popular, but [some feel](https://twitter.com/horse_js/statuses/253526104701276160) that it's not suited to large-scale application development. It doesn't have many features that other languages do -- explicit variable types, traditional classes, et cetera. JavaScript can do many of these things ([mixins](https://javascriptweblog.wordpress.com/2011/05/31/a-fresh-look-at-javascript-mixins/), for example), but they're not built into the language.

Microsoft seems to be in the camp of "JavaScript isn't suited to large-scale application development". They recently came out with [TypeScript](http://www.typescriptlang.org/), which aims to add missing features to JavaScript. It looks a lot like JavaScript. In fact, it's a superset of JavaScript, so all JavaScript code is valid TypeScript code, unlike many of [the other languages that compile to JavaScript](http://altjs.org/).

It's a superset of JavaScript
-----------------------------

Before I start talking about TypeScript features, I want to re-re-re-iterate that TypeScript is a superset of JavaScript. That means that pretty much _any JavaScript code is valid TypeScript code_. That means that TypeScript will work with any existing JavaScript libraries (I'm thinking jQuery, Backbone, whatever).

This also means that the syntax isn't going to completely confuse a JavaScript developer.

If you know the difference between C and C++, you can think of JavaScript as C and TypeScript as C++. If you don't know the difference, don't lose hope! I'll still teach you.