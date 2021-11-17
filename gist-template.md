# Explaining Regular Expression

Regular expressions will essentially check a string of characters like a password or email adress for matches to make sure that it passes our requirements (8 character long password, having a valid email etc.). Regular expression will be made to be the stopping points for situations like this. Regex can also be used for other tasks like matching characters from strings, searching for items within strings, and replacing items within strings.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

The regex that I will be describing is is an example I found on the Regular expressions MDN docs that uses the exec() method to find a match in a string. the code for this is :

var myRe = /d(b+)d/g;
var myArray = myRe.exec('cdbbdbsbz');

With this code we can search the corresponding string for the characters with the myRe variable.

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
- Matching Fixed Strings
- Matching Special Characters
- Matching Character Sets
- Specifying Groups and Fields
- Evaluating Occurrences
- Specifying Location
- Specifying Alternatives
- Matching Information from a Table
- Capturing Multiple Lines
- Managing the Scope of Analysis
### Anchors
Anchors are tokens that don't match any chracters, but will assert something about the string or the matching process.
### Quantifiers
Quantifiers will specify how many instances of a chracter, group, or chracter class must be present in the input for a match to be found/accepted.
### Grouping Constructs
Grouping constructs within regular expressions help delineate the subexpression of a regular expression and capture the substring of an input string.
### Bracket Expressions
A bracket expression is either amtching list expression of a non-matching list expression.
### Character Classes
This is a basic regex concept that refers to simply classes of characters that can match up to characters within a string.
### The OR Operator
This is used to match characters to either the right or the left of the operator.
### Flags
Flags is a way to choose different ways to match characters, for example flag s will match all characters and flag i makes the regex not case sensitive.
### Character Escapes
The character escape within regex is the backslash character. This will allow you to escape certain characters such as letters or numbers (/a, /5 etc.).
## Author

My name is Cameron McDougall, I am a full stack web developer currently studying at the the Northwestern full time bootcamp. I have a passion for front end and back end, but because of my background in the fine arts, I naturally gravitate toward front end design. GitHub: https://github.com/CJMc0d3 
