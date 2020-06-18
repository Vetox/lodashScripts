# lodashScripts
Copy of some commonly used lodash functions


Install using npm:

npm install --save https://github.com/Vetox/lodashScripts.git


import into nodejs:

var lodash = require("lodashnpm");



Functions available

_.concat(array, [values])

Creates a new array concatenating array with any additional arrays and/or values.

_.take(array, n)

Creates a slice of array with n elements taken from the beginning.

_.reverse(array)

Reverses array so that the first element becomes the last, the second element becomes the second to last, and so on.

_.fromPairs(pairs)

This method returns an object composed from key-value pairs.

_.tail(array)

Gets all but the first element of array.

_.last(array)

Gets the last element of array.

_.initial(array)

Gets all but the last element of array.

_.fill(array, value)

Fills all elements of array with value.

_.nth(array, n)

Gets the element at index n of array. If n is negative, the nth element from the end is returned. 1-indexed.

_.head(array)

Gets the first element of array.
