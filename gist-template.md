# 🌐Regex Tutorial

Introductory paragraph: This is a tutorial where the components of regular expression (regex) will be broken down into easier to understand summaries. Regular expressions are tools used for validation and pattern matching in text. This summary will cover anchors, quantifiers, grouping constructs, bracket expressions, character classes, and character escapes.

## 📝Summary

The regex the we'll be going over is /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]_)_\/?$/. This regex is used to validate urls in programming languages

## 🚀 Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## 🔧Regex Components

### Anchors⚓️

Anchors are special characters in regex that match a specific location in a string. The two main types of achors are ^ and $. The carot reprents the start of string anchors and the dollar sign is used to be the end of string anchors.

### Quantifiers🔢

Quantifiers in regular expressions control how many times a character or group appears:

- (Asterisk): Zero or more times.

* (Plus): One or more times.
  ? (Question Mark): Zero or one time.
  {n} (Curly Braces): Exactly n times.

### Grouping Constructs🧺

Grouping in regular expressions lets you:

Capture substrings: Gather specific parts of text, like grabbing phone numbers or emails. To use this, use parantheses
Quantify subexpressions: Apply repetition rules to sections, helpful for tasks like counting words or checking string length.
Combine patterns: Merge patterns for tasks like spotting words with specific start and end letters.

### Bracket Expressions🧲

Bracket expressions in regular expressions are used to match a set of characters. The characters inside the brackets are matched literally, except for the following special characters:

Caret (^): Matches any character that is not in the set.
Hyphen (-): Matches any character in the range between the two characters before and after the hyphen. For example, the regular expression [a-z] matches any lowercase letter.
Period (.): Matches any character, including newline characters.
Question mark (?): Matches the preceding character zero or one time.
Star (\*): Matches the preceding character zero or more times.
Plus (+): Matches the preceding character one or more times.

Sure. Bracket expressions in regular expressions are used to match a set of characters. The characters inside the brackets are matched literally, except for the following special characters:

Caret (^): Matches any character that is not in the set.
Hyphen (-): Matches any character in the range between the two characters before and after the hyphen. For example, the regular expression [a-z] matches any lowercase letter.
Period (.): Matches any character, including newline characters.
Question mark (?): Matches the preceding character zero or one time.
Star (\*): Matches the preceding character zero or more times.
Plus (+): Matches the preceding character one or more times.
Bracket expressions can be nested to create more complex patterns. For example, the regular expression [a-z][A-Z] matches any string that starts with a lowercase letter and ends with an uppercase letter.

Bracket expressions are a powerful tool for matching strings in regular expressions. They can be used to match a wide variety of patterns, including email addresses, phone numbers, and dates.

#### Here are some examples of how bracket expressions can be used in regular expressions:

- [a-z]: This regular expression matches any lowercase letter.

- [0-9]: This regular expression matches any digit.

- [a-zA-Z0-9]: This regular expression matches any letter or digit.

- [a-z][A-Z]: This regular expression matches any string that starts with a lowercase letter and ends with an uppercase letter.

- [0-9]{3}: This regular expression matches any string that contains exactly three digits.

### Character Classes 👥

- Character classes are a way to group together a set of characters so that they can be matched as a unit.

- In regular expressions, the character class \d is a special character class that matches any digit. This means that the regular expression [\d] will match any string that contains a single digit.

### Character Escapes🏃‍♂️

- Character escapes are used to match characters that have special meaning in regular expressions. For example, the forward slash / is a special character in regular expressions that matches a literal forward slash. To match a forward slash literally, you need to use the character escape \/.

- The escape . is used to match a period . exactly. The period . is also a special character in regular expressions that matches any character. To match a period literally, you need to use the character escape \..

## Author

This tutorial was written by [Owen Warner](https://github.com/opwar-bc).
