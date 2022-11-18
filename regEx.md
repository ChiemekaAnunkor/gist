# Regular Expression Tutorial

The purpose of this Gist is to explain what are regular expessions and how we can use them in Javascript. Wikipedia describes regular expressions as "A regular expression (shortened as regex or regexp;[1] sometimes referred to as rational expression[2][3]) is a sequence of characters that specifies a search pattern in text. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. Regular expression techniques are developed in theoretical computer science and formal language theory."

## Summary

This code will be used in the tutorial to give a real world examples for how to use regex. This focuses on email matching to validate user input matches the correct format.
```
- Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
```
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
Anchors are used to start and end a regular expression
they are ``` ^``` to start and ``` $``` at the end of  
every regular expression is wrapped wth ``` //```  then the anchors are added

### Quantifiers
 learn microsoft specifies quantifiers as " Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. "
 <img width="446" alt="image" src="https://user-images.githubusercontent.com/63639477/202624416-a7203070-1bfc-4395-b382-8d7ad2f3f888.png">


### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
