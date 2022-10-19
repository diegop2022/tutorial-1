# Matching an Email

Tutorial explaining the regex for verifying a valid user input email address.

## Summary

The regex matching an email is an express that is used to verify that user input is a valid email address. Each area of the regex has a unique function to make sures that a user enters in an email address that follows the normalized email address template.

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
**/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/**

### Anchors
The anchors in the email validation regex are **^** and **$**. The caret anchors matches the beginning of the text while the dollar anchor matches the end of the text.
### Quantifiers

### OR Operator
Contains no **OR** operators

### Character Classes
The email validation regex contains a digit character class denoted by **\d**. The regex also contains a dot character **"."** which will match any character except the newline character.

### Grouping and Capturing
The email validation expression contains group capturing using parentheses**()** to encaption the values between the parentheses grouping them together.

### Bracket Expressions
We see in the expession they use bracket expressions **[]** to determine the range of possible values to be entered in the exp

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
Written by Diego Pena
https://github.com/diegop2022 
