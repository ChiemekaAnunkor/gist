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
```/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/```
### Quantifiers
 learn microsoft specifies quantifiers as " Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. " 

Below are examples of quantifiers


<img width="446" alt="image" src="https://user-images.githubusercontent.com/63639477/202624416-a7203070-1bfc-4395-b382-8d7ad2f3f888.png">


from our email example we have ```+```

### Grouping Constructs
When using grouping contructs,  you can use parantheses for capturing groups of words/characters or numbers,  i.e ```()```
from our email example we have this 
```([a-z0-9_\.-]+) ```


### Bracket Expressions

A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

An example from the email regex would be ```[a-z0-9_\.-]```
### Character Classes
a “character class”, also called “character set”, you can tell the regex engine to match only one out of several characters.
An example from the email regex would be ```[a-z\.]```

### The OR Operator
The or operator is ```|```, this allows us to search for a value if its not there we can search a different value simulatneously 
for exmaple ```[e|a] ```

### Flags

Javascript.info gives great examples of glags, They are added at the end to effect the entire search 

There are only 6 of them in JavaScript:
```i```
With this flag the search is case-insensitive: no difference between A and a (see the example below).
```g```
With this flag the search looks for all matches, without it – only the first match is returned.
```m```
Multiline mode (covered in the chapter Multiline mode of anchors ^ $, flag "m").
```s```
Enables “dotall” mode, that allows a dot . to match newline character \n (covered in the chapter Character classes).
```u```
Enables full Unicode support. The flag enables correct processing of surrogate pairs. More about that in the chapter Unicode: flag "u" and class \p{...}.
```y```
“Sticky” mode: searching at the exact position in the text (covered in the chapter Sticky flag "y", searching at position)

### Character Escapes
 google defines it as "The backslash character ( \ ) is the escaping character. It can be used to denote an escaped character, a string, literal, or one of the set of supported special characters. Use a double backslash ( \\ ) to denote an escaped string literal. For more information, see Escaping Strings in Transformations."
 for exmaple ```\\```

## Author
This tutorial was create by Chiemeka Anunkor.
Contact me at:

[GitHub](https://github.com/ChiemekaAnunkor) ,[Email](anunkorcc@gmail.com)
, [LinkedIn](https://www.linkedin.com/in/chiemeka-anunkor-98ba721b0/)


