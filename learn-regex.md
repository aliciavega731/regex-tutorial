![Banner](./assets/Learn-Regex1.gif)

# What is RegEx?

Regular expressions, better known as regex or regexp, are one of the most effective and widely used programming techniques. They are text strings that describes a search pattern and is mostly used string matching. You can think of it as “find and replace” tool we've known to appreciate in document applications. They are available in almost every language and help us to verify user input, conduct searches, and even test code.

Pro tip: You can use [RegExr](https://regexr.com/) to test out your regex.

## Summary

After researching and gaining a better understanding of what different parts of a regular expression do, I will explain what they do for a specific regex. Specifically, matching an email:

    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

Anchors are used to determine if the corresponding symbol is the input string's beginning or ending symbol. There are two kinds of anchors: The caret `^` and the dollar sign `$`. In conclusion, the caret checks whether the matching character is the first character of the input string while the dollar sign checks whether the matching character is the last character of the input string.

Both anchors are evident in the example expression. 

### Quantifiers

Quantifiers are denoted by curly braces `{}` and it contains either the exact quantity or the quantity range of characters to be matched.

The `{2,6}` quantifier can be found in the third group of the expression and it matches between 2 and 6 of the preceding character set.

### OR Operator

The OR opertator, or alternation, is denoted by the pipe symbol `|`, which enables one of two subexpressions to be matched. For example, the regex `apples|bananas` will match the text apples and the text bananas.

### Character Classes

Character classes, or character sets, are denoted by a square brackets `[]`, which match any of the characters withing the brackets. By default, the match is case-sensitive.

There are three character sets in the expression. Each character set in the expression is unique but all of them are looking to match a character in the range of a-z. 

### Flags

Flags, or modifiers, modify the output of the regular expression and can be used in any order. Some common flags include: 

- Ignore case `i` that makes the whole expression case-sensitive. 
- Global search `g` that retains the index of the last match, allowing subsequent searches to start from the end of the previous match.
- Multiline `m` that will match the start and end of a line, instead of the start and end of the whole string within the two anchors.

### Grouping and Capturing

Grouping characters in a regular expression are denoted by parenthesis `(...)`. 

In the example expression, there are three capturing groups and can be found by the start of the opening parenthesis and the closing parenthesis.

### Greedy and Lazy Match

In very basic terms, <span style="color: red;">greedy</span> match means the expression will match the largest possible group, while on the other hand, <span style="color: green;">lazy</span> will match the smallest possible group. 

    ^(\w+)(B+)$          (greedy)
    ^(\w+?)(B+)$         (minimal)

### Boundaries

Word boundaries `/b` matches a word boundary position (start / end of string) between a word character and a non-word character or position. Any location that isn't a word border is matched by not word boundaries `/B`. This corresponds to a location rather than a character.

### Back-references

In a regular expression, a backreference detects a previously matched category and searches for the same text again. When you want to search for recurring words in a letter, you can use backreferences.

### Look-ahead and Look-behind

SOMETHING HERE

## Author

I am currently a University of Arizona coding bootcamp student with her eyes set on front-end web development. Let's connect. 

- [Alicia Vega's Github](https://github.com/aliciavega731)
