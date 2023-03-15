# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
&nbsp;
* Anchors: ^ and $ match the start and end of a line respectively.

* Quantifiers: *, +, ?, {n}, {n,}, and {n,m} specify the number of times a character or group of characters should occur.

* OR operator: | matches either one expression or another.

* Character classes: [] match a single character from a group of characters.

* Flags: g, i, m, u, and y modify the behavior of the regex.

* Grouping and capturing: () group subpatterns together and extract specific parts of the match.

* Bracket expressions: [] match any character within a specified range or set.

* Greedy and lazy match: *, +, and ? can be made lazy by adding ?.

* Boundaries: \b and \B match specific positions that are not characters.

* Back-references: \n refer to a previously matched group in the regex.

* Look-ahead and look-behind: (?=...), (?!...), (?<=...), and (?<!...) match patterns only if they are followed or preceded by another pattern without including the pattern in the match.

&nbsp;

## Anchors
&nbsp;

Anchors are used to match specific positions in the text. In these cases, the caret anchor is used to indicate the start of a line, while the dollar sign anchor is used to indicate the end of a line.

&nbsp;

## Quantifiers
&nbsp;

The quantifier is used when a character or group of characters should appear multiple times. Quantifiers most commonly used

&nbsp;


‘*’ : Matches zero or more occurrences of
the preceding character.

‘+’; Matches one or more occurrences of the preceding character.

‘?’ : Matches zero or one occurrence of the preceding character.

‘{n}’ : Matches exactly n occurrences of the preceding character.

‘{n,}’ : Matches exactly n occurrences of the preceding character.

‘{n,m}’: Matches between n and m occurrences of the preceding character.

The OR operator is represented by the vertical bar | Using OR in regex, you can match either a term or expression. For example, this regex matches one of the terms, "cat" or "dog".

/cat | dog/

&nbsp;

## OR Operator
&nbsp;

The OR operator is represented by the vertical bar | Using OR in regex, you can match either a term or expression. For example, this regex matches one of the terms, "cat" or "dog".

/cat | dog/


&nbsp;

## Character Classes
&nbsp;

An individual character can be matched against a group of characters by using a character class. Square brackets  [ ] ~ are used to specify a character class. A regex matching any lowercase vowel might look like this:

/[aeiou]/

&nbsp;

## Flags
&nbsp;

Flags are used to modify the behavior of a regex. The most common flags include:

"g': Matches all occurrences of the pattern.

"i : Matches regardless of case.

m': Treats the string as multiple lines.

"u: Treats the pattern and input as unicode.

• 'y': Matches starting at the last match position.

After the last slash /, flags are added. For example, the following regex matches all occurrences of the word "the" regardless of case: 

/the/gi

&nbsp;

## Grouping and Capturing
&nbsp;

Subpatterns are grouped together and specific parts of matches are extracted using grouping and capturing. Parentheses " () " are used to group subpatterns. As an example, the following regex captures usernames and domains from email addresses:

/^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+\.[a-zA-Z]{2,})$/

&nbsp;

## Bracket Expressions
&nbsp;

Bracket expressions are used to match any character within a specified range or set. For example, the following regex matches any digit:

/[0-9]/

&nbsp;

## Greedy and Lazy Match
&nbsp;

By default, regex matching is greedy, which means it will match as much as possible.
However, it is possible to specify a lazy match using the ? quantifier. For example, the following regex matches the first occurrence of "foo" followed by "bar":

/foo.*?bar/


&nbsp;

## Boundaries
&nbsp;



## Back-references

## Look-ahead and Look-behind

## Author

By Fabien Mukungu Acina

https://github.com/Fabitheguy003

