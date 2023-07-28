# REGEX (Regular Expression Tutorial)

Regular expressions, commonly known as regex, are powerful tools used for pattern matching and text manipulation in programming. They consist of a series of special characters that define a specific search pattern. By using regex, programmers can efficiently find and manipulate strings in various programming languages, offering a flexible and comprehensive solution to handle complex search scenarios that basic string methods may struggle to address.
## Summary

In this tutorial, we will explore the functionality of a specific regular expression (regex) by breaking down each part of the expression and explaining its purpose. Regular expressions are sequences of characters that define search patterns used to find specific character patterns within a string or validate input. Our focus will be on understanding the regex /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/, which validates email addresses. Each component of this regex plays a unique role in ensuring that the user's input matches the required email address format. By studying and understanding the different parts of this regular expression, we can gain insight into how regex works and how it can be applied in web development.

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

Anchors in regular expressions are represented by the caret (^) and dollar sign ($). The caret (^) is used to signify that the match should begin at the start of the string, while the dollar sign ($) indicates that the match should end at the end of the string. For example, the regex /^The/ will match strings that start with "The," but not "the" or "The person." We will explore how anchors work and their role in defining the starting and ending points of a regex match.

### Quantifiers

Quantifiers in regular expressions define the number of times a preceding element should occur in the string. Common quantifiers include *, +, ?, and {}. For instance, the pattern [a-z]{3,5} specifies that there should be 3 to 5 consecutive lowercase letters in the string. We will delve into various quantifiers and understand how they enable us to set repetition limits for matching patterns.

### OR Operator

The OR operator (|) allows us to specify alternatives in a regex. It matches either the expression on its left or the one on its right. For example, (a|b|c) matches either "a," "b," or "c" in the input string. We will explore how the OR operator helps us provide multiple choices within a regex and how to use it effectively.

### Character Classes

Character classes in regular expressions define sets of characters that can match a single character in the input string. For instance, \d matches any Arabic numeral digit, equivalent to the range [0-9]. We will learn about various character classes like \d, \w, \s, and their inverse counterparts, as well as how they enhance the flexibility of regex patterns.

### Flags

Flags in regular expressions are optional modifiers placed after the closing slash (/) that provide additional functionality or limits to the regex. The commonly used flags include "g" for global search, "i" for case-insensitive search, and "m" for multi-line search. We will explore the purpose and usage of these flags in regex.

### Grouping and Capturing

Grouping constructs in regular expressions are represented by parentheses (()). They are used to create subexpressions and enable us to apply quantifiers or logical operators to specific parts of the regex. Capturing groups allow us to capture and reuse matched character sequences for backreferences. We will examine how grouping constructs work and their significance in organizing and reusing parts of a regex.

### Bracket Expressions

Bracket expressions, enclosed within square brackets ([]), define ranges or sets of characters that we want to match in the input string. These expressions allow us to search for specific character patterns, such as [a-z] for any lowercase letter from 'a' to 'z'. We will explore the concept of bracket expressions and understand how they help define positive character groups.

### Greedy and Lazy Match

Quantifiers in regular expressions are greedy by default, meaning they match as many occurrences as possible. However, adding the ? symbol after a quantifier makes it lazy, matching as few occurrences as possible. We will learn about the difference between greedy and lazy matching and their implications in regex.

### Boundaries

Boundaries in regular expressions represent positions in the input string where certain conditions are met. Common boundaries include \b for word boundaries and \B for non-word boundaries. We will explore how boundaries enable precise matching of specific positions in the text.

### Back-references

Back-references in regular expressions allow us to refer to captured groups within the same regex pattern. They are achieved by using \1, \2, etc., where the number corresponds to the order of the capturing group. We will understand how back-references work and how they simplify complex regex patterns.

### Look-ahead and Look-behind

Look-ahead and look-behind assertions are zero-width assertions that assert specific conditions without including the matched text in the result. They allow us to specify patterns that must (or must not) be followed by or preceded by certain expressions. We will explore look-ahead and look-behind and their applications in advanced regex patterns.

## Author

Arun Mundackal
GitHub: [GenjutsYou](https://github.com/GenjutsYou)