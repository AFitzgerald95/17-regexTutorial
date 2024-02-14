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

### Bracket Expressions

### Character Classes

### The OR Operator

the OR Operator is signified by the vertical bar '|' and allows you search multiple alternatives for a pattern.

ex. chicken|beef - Matches "Chicken" or "Beef" in text.

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
