![Banner](./assets/Learn-Regex1.gif)

# What the heck is RegEx?

Regular expressions, better known as regex or regexp, are one of the most effective and widely used programming techniques. They are text strings that describes a search pattern and is mostly used string matching. You can think of it as “find and replace” tool we've known to appreciate in document applications. They are available in almost every language and help us to verify user input, conduct searches, and even test code.

## Summary

--CHANGE TEXT HERE-- Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

You can use RegExr (https://regexr.com/) to test out your regex.

Matching an email:

    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

Anchors are used to determine if the corresponding symbol is the input string's beginning or ending symbol. There are two kinds of anchors: The caret ^ checks whether the matching character is the first character of the input string, and the dollar sign $ checks whether the matching character is the last character of the input string.

The regex ^Monkeys: my mortal enemy$ will completely match the text Monkeys: my mortal enemy but not match Spider Monkeys: my mortal enemy or Monkeys: my mortal enemy in the wild. The ^ ensures that the matched text begins with Monkeys, and the $ ensures the matched text ends with enemy.

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
