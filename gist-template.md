# Regex-Tutorial


A regex can be used when you're trying to match a certain character combination within a string. This page will break down how to validate email addresses.

## email code

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Summary

The previously listed code can be used to find or validate emails.

## Table of Contents

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

## Regex Components

### Anchors
The anchor is what starts and ends the regular expression in the email code.

Anchors = ^ and $

### Quantifiers

Quantifiers are used to determine how many times a specific character or group of characters needs to be present in order to have a match.

### OR Operator

[] is used for OR operators. Everything between the brackets is an OR Operator.

### Character Classes
\d  ensure that a letter is matched after the @ instead of numbers or special characters.

### Flags
/regex/ the expression g is used for global, m is multiline and i means insenstive.

### Grouping and Capturing

Parentheses create a capturing group. It's important to properly match your groups.

### Bracket Expressions

This section will be the same as the or operator section.

### Greedy and Lazy Match

Theres's no lazy or greedy match in this code.

### Boundaries
This code doesn't use boundaries.

### Back-references

This code doesn't use back references.


### Look-ahead and Look-behind

If using a look-ahead or look-behind, then it has to match in a certain order. It is not being used in the code used for this email validation.

## Author

This tutorial was created by Janea Smith 
https://github.com/jaysmith13
