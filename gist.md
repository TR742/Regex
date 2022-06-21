# Regex Tutorial

Welcome to a Regex Tutorial! Here you will learn 

## Summary

Regex, or Regular Expressions, are special characters in a search pattern that help with validation. See the following code as an example to match an Email!

```
Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
```
Use the table of contents below to find out what this regular expression means!

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

Anchors are used at the beginning and the end of your regex. The ^ is used at the beginning and signifies a string that begins with the characters that follow it. In our code, the characters that follow the ^ are a-z0-9

The $ anchor is used at the end of the regex and signifies a string that ends with the characters that precede it. Within our code, the characters would be a-z.

Anchors look for characters that are within brackets [], or a string value such as "This string value".

### Quantifiers

Quantifiers give a range of characters allowed. This is always wrap in {}. Within our code, the range given is between 2 and 6 characters.

### Grouping Constructs

There can be multiple validations with a regualr expression, Grouping Contructs ensures that the group in the expression passes before it can then move onto the next group.

### Bracket Expressions

Bracket expressions are used to set the range allowed for characters in the email. In our regex, the range given is a-z and 0-9, however these ranges can include special characters, lowercase or uppercase letters, and numbers and can be set to any range you would like.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)