# String Methods

## Static Methods (found in the String constructor)

`String.fromCharCode()` - make a string from (UTF-16) code units
`String.fromCodePoint()` - as above but more precise

^^ You will NOT use.

## Instance methods (found in each array) (deprecate methods have been removed)

`x`s represent likelyhood of use

xxx   `charAt()` - same as str[n]
      `charCodeAt()` - like charAt but gives code
      `codePointAt()` - like charAt but gives codePoint
      `concat()` - join 2 strings
xxx   `endsWith()` - checks if a string ends with some letters
xxxx  `includes()` - straightforward match of a character (returning boolean)
xxxx  `indexOf()` - straightforward match of a character (returning index of first match or -1, if not found)
xxx   `lastIndexOf('str', idx)`- searches backwards from (optional) idx
      `localeCompare()` - compares strings of different locales for alphabetic order
xxx   `match()` - return an array of all the matches for a regular expression
xx    `matchAll()` - return an iterator of all the matches for a regular expression, inc. capture groups
      `normalize()` - normalise unicode charaters
xx    `padEnd(n, chars)` - add 'n' chars to the end of a string
xx    `padStart(n, chars)` - add 'n' chars to the start of a string
xx    `repeat(n)` - creates a new string by repeating the old one 'n' times
xx    `replace()` - replaces the first instance that matches text or regex
xxx   `replaceAll()` - replaces all instances that match text or regex
xx    `search()` - searches with a regex and returns the first index of a match
xxxx  `slice()` - makes a copy of part of the string
xxxx  `split()` - splits the string into an array of sub-strings
xxx   `startsWith()` - checks if a string starts with some letters
      `substring()` - better version of substr; like slice. use slice
xx    `toLocaleLowerCase()` - like toLowerCase but language/location sensitive
xx    `toLocaleUpperCase()` - like toUpperCase but language/location sensitive
xxx   `toLowerCase()` - turns the string lowercase
      `toString()` - method override to ensure the string is returned properly (you don't use)
xxx   `toUpperCase()` - turns the string uppercase
xxx   `trim()` - gets rid of whitespace at both ends
xx    `trimEnd()` - gets rid of whitespace at the end
xx    `trimStart()` - gets rid of whitespace at the start
      `valueOf()`- gets actual text if String('hello')
      `[@@iterator]()` - for internal use. It allows loops to iterate over the string

x.     `String.raw()` - is a 'tagged template literal' it allows you to do : ``` String.raw`C:\Development\profile\aboutme.html`; ``` without escaping the slashes
