# Array Methods

## Static Methods (found in the Array constructor)

`Array.from()` - turns things into an array (e.g. `Array.from(arguments)`)
`Array.isArray()` - tests if something is an array
`Array.of()` - A mended version of the Array constructor (ignore)

## Instance methods (found in each array)

`x`s represent likelyhood of use

xx    `concat` - Join 2 arrays
x     `copyWithin` - Move items around inside the array
xx    `entries` - make an iterator that returns the entries `[key, value]` (ignore)
xxx   `every` - test if all pass a criterion
xx    `fill` - Fill up part of an array with something
xxxx  `filter` - Find many
xxxx  `find` - Find one
xxxx  `findIndex` - Find where one is
x     `flat` - Turn [[1,2], [3,4]] into [1,2,3,4]
x     `flatMap` - Do what `flat` does BUT transform the values like `map` does
xx    `forEach` - iterate (use `for...of`)
xxx   `includes` - Test if a simple concrete [often primative] value is present
xxx   `indexOf` - Find where simple value is
xx    `join` - Turn array into string (with separators)
xx    `keys` - make an iterator that returns the keys (ignore)
x     `lastIndexOf` - Find the last index that a certain item is present 
xxx   `map` - create a new array of values by transforming the values in this array
xxxxx `pop` - remove and return the last item
xxxxx `push` - put an item onto the end of the array
xx    `reduce` - reduce all the values in an array down to one (e.g. add them all up)
x     `reduceRight` - Same as reduce but start at the other end
xx    `reverse` - change the order
xxx   `shift` - put something on the front of an array
xxxx  `slice` - copy part of the array
xxx   `some` - test if some items pass a test
xxx   `sort` - sort things (-1, 0, 1 to move left, stay, right)
xxx   `splice` - delete (and maybe insert) parts of this array
x     `toLocaleString` - process the things in this array to suit your current location (e.g. currency, time, etc.)
      `toSource` - DON'T USE!!!
x     `toString` - turn into a string (minus the `[]`s)
xx    `unshift` - put something on the front of the array
xx    `values` - make an iterator that returns the values (ignore)
