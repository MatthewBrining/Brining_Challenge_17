# Regex tutorial 

This repository will summarize the use of Regex or regular expressions when applied to coding applications. The example case used will be matching an email

## Summary

This tutorial will cover the usage of matching an email. In regex this looks like the following code: 

### /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
    Anchors do not match characters. Instead they match positions
### Quantifiers
    Quantifiers look at how many times a character is present
### OR Operator
    OR operator functions similar to how we are familiar with in coding, looking for instances that match a logical "OR" statement. i.e. find cases where cats OR dogs are present (triggering in either case)
### Character Classes
    Distinguish between types of classes such as letter and numbers
### Flags
    optional flags allow for improved search functionality by allowing, as an example, to ignore case. 
### Grouping and Capturing
    Quite literally a method of grouping multiple characters to treat as a whole. 
### Bracket Expressions
    Either a matching list expression or a non-matching. Regex brackets work in a predictable way when compared to the code we are familiar with. 
### Greedy and Lazy Match
    Greedy matches the longest possible string, lazy does the opposite. In practice this can grab matches when only a few characters are entered in a similar way to an auto-complete. 
### Boundaries
    typically the boundary between a word and a non-word character
### Back-references
    references a previous part of a matched regular expression
### Look-ahead and Look-behind
    Does what it says on the tin. Either checking ahead or behind the cursor position when parsed to determine a match. 
## Author
Matthew Brining