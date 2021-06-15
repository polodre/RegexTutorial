# RegexTutorial

# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

A regular expression is a pattern that is matched against a subject string from left to right.
Regular expressions are used to replace text within a string, validating forms, extracting a
substring from a string based on a pattern match.

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

There are also two types of regular expressions: the "Basic" regular expression, and
the "extended" regular expression. A few utilities like awk and egrep use the extended
expression. Most use the "basic" regular expression. If you want to match for the
actual '+', '. ' etc characters, add a backslash( \ ) before that character. This
will tell the computer to treat the following character as a search character and
consider it for matching pattern. Example : \d+[\+-x\*]\d+ will match patterns
like "2+2" and "3*9" in "(2+2) * 3\*9".

### Anchors

In regular expressions, we use anchors to check if the matching symbol is the
starting symbol or ending symbol of the input string. Anchors are of two types:
The first type is the caret `^` that checks if the matching character is the first
character of the input and the second type is the dollar sign `$` which checks if a matching
character is the last character of the input string.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.
Nesting quantifiers (for example, as the regular expression pattern (a*)* does) can increase the number of comparisons that the
regular expression engine must perform, as an exponential function of the number of characters in the input string.
If the \*, +, ?, {, and } characters are encountered in a regular expression pattern, the regular expression engine
interprets them as quantifiers or part of quantifier constructs unless they are included in a character class. To
interpret these as literal characters outside a character class, you must escape them by preceding them with a backslash.

### Grouping Constructs

Grouping constructs delineate the subexpressions of a regular expression and capture the substrings
of an input string. You can use grouping constructs to do the following: Match a subexpression that
is repeated in the input string.

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
