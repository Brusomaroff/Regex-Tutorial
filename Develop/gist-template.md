# Regex Tutorial

Regex is a regular expression is a pattern that the regular expression engine attempts to match in input text. A pattern consists of one or more character literals, operators, or constructs.

## Summary

I will be going over the Regex for an email. Each character has its own parameter The Regex format for email is: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ This means it begins with characters within those parameters followed by an @ symbol and then characters after which would be its domain.

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
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
The /^ means its the beggining/start of the string and the $/ means its the end/close of the string.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

### Character Classes
- a-z refers to "a" to "z"
- 0-9 refers to "0" to "9"
- "-" is "-"
- "." Escapded character is a "." character
- @ is an "@" character
- \d matches single character that is a digit --> 0 - 9

### Grouping and Capturing
([a-z0-9_.-]+), ([\da-z.-]+) and ([a-z.]{2,6}) this is the grouping and parameters that will give the result.

### Boundaries
The word boundary \b matches positions where one side is a word character and the other side is not a word character.

### Look-ahead and Look-behind
There’s a special syntax for that, called “lookahead” an “lookbehind”, together referred to as “lookaround”. An example of Lookahead is this: The syntax is: X(?=Y), it means "look for X, but match only if followed by Y". There may be any pattern instead of X and Y. A look behind is that it allows to match a pattern only if there’s something before it.

## Author

Hey there! Im Bryson and this is my Github: https://github.com/Brusomaroff
