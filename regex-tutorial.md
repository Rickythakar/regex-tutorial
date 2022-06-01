# Regex Tutorial

This is a simple tutorial on regular expressions for Javascript. Below you can find a table of contents that can navigate you to the different sections of the tutorial.
Hope you enjoy and benefit from this tutorial.

## Summary

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. 

The regex I will be describing is the following
/^.*$/i 
will bring back "Ilove2CODE"


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
Anchors are characters that are within the regex and allow the user to search for strings that match the begining or ending.

Expression	Description

[^abc]	Find any character NOT between the brackets
[^0-9]	Find any character NOT between the brackets (any non-digit)

### Quantifiers
Quantifiers define how many characters are with the regex, which helps the user specifiy how many instances a characters.
Below you can find some examples of quantifiers.
.*	Matches any string that contains zero or more occurrences total
n*	Matches any string that contains zero or more occurrences of n
n+	Matches any string that contains at least one n


### Grouping Constructs
In regex constructs can be grouped using paranthesis.
The following regex (123):(abc)
would be considered two groups.


### Bracket Expressions
Sqaure brackets in regex represents a range of characters that the user would like to match. Bracket expressions will use the range of characters in any order to search for regex that match the parameters.

### Character Classes
Character classes tells the regex whether there is a specific whitespace, digit, or a alphabet.


### The OR Operator
The OR operator can be written as the following "|" and it literally means or.
The OR operator can be used within javascript when assigning if else statements as well as regex expressions.

### Flags
Flags are one of the optional parameters of a regex. The define the limits for the regex. Some examples can be found below.
g-Global search (searches globally for all possible matches in a string)
i-Case sensitive search (will decide if the regex should ignore case when searching for a string)
m-multi line search (searches multiple lines for the matching string)

### Character Escapes



## Author
Ricky Thakar - Aspiring full stack web developer currently a student at UCF Coding bootcamp
Github username:
https://github.com/Rickythakar
