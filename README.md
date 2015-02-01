# json-extend

Deep extend utility designed for use with JSON data.

Syntax: `extend ( target, object1[, objectN] )`

Extend one object with one or more others, returning the modified object.

# Why this utility

If you use JSON APIs to populate your app models, there are a fewer types to deal with,
so this library can optimize for handling just those cases (Object, Array, Boolean, String, Number, and null).
