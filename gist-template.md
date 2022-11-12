# Title (replace with your title)

This is a tutorial about using the ReExp.prototype.exec() regex method. Its purpose is to inform, educate, and excite you about the exec() method.

## Summary

The exec() method searches strings and returns either an array or null value. Some sample code:
const regex1 = RegExp('foo\*', 'g');
const str1 = 'fishing, swimming';
let array1;

while ((array1 = regex1.exec(str1)) !== null) {
console.log(`Found ${array1[0]}. Next starts at ${regex1.lastIndex}.`);

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

The exec() method just requires a string to be input.

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

This tutorial was written by Kayla Hancock who can be found at:
https://github.com/KayHancock
