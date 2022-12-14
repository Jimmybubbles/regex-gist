# Regex for Hex Value

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Summary

A Regex is a sequence of characters that define a specific search pattern. when regex is included in code it can be used to find certain patterns of characters within a string, or find and replace a character or sequence of characters in a string. regex is used alot of the time to validate input as it can be crafted to only pass specific input. 

this tutorial is for regex of Hex Values. 

## Table of Contents

- [Regex for Hex Value](#regex-for-hex-value)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
    - [Anchors](#anchors)
    - [Quantifiers](#quantifiers)
    - [OR Operator](#or-operator)
    - [Character Classes](#character-classes)
    - [Flags](#flags)
    - [Grouping and Capturing](#grouping-and-capturing)
    - [Bracket Expressions](#bracket-expressions)
    - [Greedy and Lazy Match](#greedy-and-lazy-match)
    - [Boundaries](#boundaries)
    - [Back-references](#back-references)
    - [Look-ahead and Look-behind](#look-ahead-and-look-behind)
  - [Author](#author)

## Regex Components

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

### Anchors

the caret symbol (^) and the dollar symbol ($) are anchors in the hex regular expression, the Caret symbol is the strings starting point and the dollar symbol is the strings end point.

- example code Caret /^abc/
- example code Dollar /abc$/

### Quantifiers

the quantifiers are identified as the curly braces {} and the ?. The curly braces matches a string and the ? demonstrates that the expression must match once or not at all.

- example code abc{1} matches the string that has ab followed by one c
- example code abc{1,10} matches a string that has ab followed by 1 up to 10 c

### OR Operator

the | (or) operator is used to define an expression to look for a specific character or set of characters 

this set [a-f0-9]{6} | (or) [a-f0-9]{3} this set


### Character Classes

Not applicable to regex for hex value

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

Not applicable to regex for hex value

### Back-references

Not applicable to regex for hex value

### Look-ahead and Look-behind

Not applicable to regex for hex value

## Author

james russell 

