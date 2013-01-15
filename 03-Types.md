New TypeScript feature 1: types
===============================

If TypeScript didn't have types, that'd be like...well, I guess it wouldn't be like Ruby not having rubies. Bad example. Let's talk about types.

Normal primitive types: number, boolean, string
-----------------------------------------------

TODO

The any type
------------

TypeScript has a type called `any`. To quote the language specification, "the type 'any' means that a tool can assume nothing about the shape or behavior" of the variable. It can be a `number` or a `bool` or a `string` or whatever you damn please.

That means the code below is totally fine:

    var x: any = 5
    x = 'hello'

The `any` type is a lot like regular variables in JavaScript. In JavaScript, something that was once a number can become a string. TypeScript allows you to do that with the `any` keyword.

Whenever TypeScript can't infer a type, it becomes any.

    function say(something) {    // something is of type "any"
        alert(something);
    }

    var foo = null;              // foo is of type "any"

Weird types: undefined and null
-------------------------------

Just like in JavaScript, the `undefined` and `null` types are a little weird.

TODO
