# A Brief Overview of Regular Expressions

Regular Expressions, more commonly known as regex are a sequence of characters that make up a specific pattern used to match with strings within a block of code. Programmers use regex to modify text based on the criteria provided in their expressions. Understanding regex is important for the development of your skills as a programmer as it can expand your knowledge base in areas of text processing, data validation and more!

## Summary

This document will discuss several components of regular expressions including anchors, quantifiers, grouping constructs, bracket expressions, character classes, the OR operator, flags, and character escapes.

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

### Anchors

Anchors are special characters that represent a position in a string and are used to specify the beginning and end of a string where a match should occur.

* '^' Matches the beginning of a line whereas '$' will match the end of a line.

ex. ^Alpha Omega$

### Quantifiers

Quantifiers are special characters that dictate the number of occurrences of a character or group in a pattern.

* '*' - Zero or more times

* '+' - One or more times

* '?' - Zero or one time

* '{}' - Can provide three different ways to set limits for a match:

    *  { n } - Matches the pattern exactly 'n' number of times

    *  { n, } - Matches the pattern at least 'n' number of times

    *   {n, x } - Matches the pattern from a minimum of 'n' number of times to a max of 'x' number of   times 

ex. \d{1,3} Matches 1-3 consecutive digits

### Grouping Constructs

Grouping constructs allow you to treat multiple characters as a one group, the way you group a section is by using the parentheses '()'.

ex. (hello){3} - Would Match 'hellohellohello'

### Bracket Expressions

Bracket expressions in regex specify a range of characters to match like [abc] which will look for a string that has 'a', 'b', or 'c'.

ex. [a-z] matches lowercase letters and [0-9] matches numbers

### Character Classes

Define sets of characters that can execute a match in an input string.

ex. \d - Matches any numerical digit.

### The OR Operator

the OR Operator is signified by the vertical bar '|' and allows you search multiple alternatives for a pattern.

ex. chicken|beef - Matches "Chicken" or "Beef" in text.

### Flags

Flags are places after the second slash to define to define additional functionality. Common flags include a 'g' for global search, 'i' for case-insensitive search and 'm' for multi-line search

ex. /regex/gi; matches "regex" globally and case insensitively

### Character Escapes

Character Escapes signified by the '\' are used to escape special characters like '{}' allowing literal interpretation. This applies universally, except in bracket expressions.

ex. \.\d - '\.' represents a literal period and '\d' represents a literal digit. 

## Author

This document was composed by Austin Fitzgerald, a student of the UCF Full-Stack Bootcamp. You can view more work [here](https://github.com/AFitzgerald95).