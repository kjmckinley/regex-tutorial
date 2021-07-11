# RegEx Tutorial

This tutorial will serve as a crash-course in how to utilize RegEx, otherwise known as Regular Expression. As denoted in the name RegEx uses various Expressions to find specific patterns of characters that are in any given string, or in order to replace one or more characters with something else in any given string. The following breakdown will explain how these Regular Expressions as the parameters of how we will search for, as well as validate data.

## Summary

Example --> The following regular expression can be used to verify that user input is a valid email address. This tutorial will serve to breakdown the contents of the snippet below in order to explain exactly how it works to find and validate data.

Snippet:  `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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
Characters that are within a Regular Expression that target as well as denote the beginning and end of a set of strings are called Anchors. For instance, the `^` character in the above example will match the beginning of the target string, while the `$` will match the end of the target sting. To further explain the functionality of these anchors, say we took 2 different emails, `name@email.com` and `name@email.coooom` and tried to validate them using the above Regular Expression (`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`), only `name@email.com` would be validated since it is within the parameters or `Qualifiers` in the expression.

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
