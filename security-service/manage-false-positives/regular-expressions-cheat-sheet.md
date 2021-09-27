# Regular Expressions Cheat Sheet

A regular expression \(regex or regexp\) is a sequence of characters that specifies a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

The below tables assists you on how to use different regular expressions:

## Regular Expression Basics 

| **Character** | Explanation  |
| :--- | :--- |
| . | Anything. Any character except newline |
| a | The character a |
| ab | The string ab |
| a\|b | a or b |
| a\* | 0 or more a's |
| \ | Escapes a special character |

## Regular Expression Quantifiers

| **Character** | **Explanation** |
| :--- | :--- |
| \* | 0 or more |
| + | 1 or more |
| ? | 0 or 1 |
| {2} | Exactly 2 |
| {2, 5} | Between 2 and 5 |
| {2,} | 2 or more |

## Regular Expression Groups 

| **Character** | **Explanation** |
| :--- | :--- |
| \(...\) | Capturing group |
| \(?P&lt;Y&gt;...\) | Capturing group named Y |
| \(?:...\) | Non-capturing group |
| \(?&gt;...\) | Atomic group |
| \(?\|...\) | Duplicate group numbers |
| \Y | Match the Y'th captured group |
| \(?P=Y\) | Match the named group Y |
| \(?R\) | Recurse into entire pattern |
| \(?Y\) | Recurse into numbered group Y |
| \(?&Y\) | Recurse into named group Y |
| \g{Y} | Match the named or numbered group Y |
| \g&lt;Y&gt; | Recurse into named or numbered group Y |
| \(?\#...\) | Comment |

## Regular Expression Character Classes

| **Character** | **Explanation** |
| :--- | :--- |
| \[ab-d\] | One character of: a, b, c, d |
| \[^ab-d\] | One character except: a, b, c, d |
| \[\b\] | Backspace character |
| \d | One digit |
| \D | One non-digit |
| \s | One whitespace |
| \S | One non-whitespace |
| \w | One word character |
| \W | One non-word character |

## Regular Expression Assertions

| **Character** | **Explanation** |
| :--- | :--- |
| ^ | Start of string |
| \A | Start of string, ignores m flag |
| $ | End of string |
| \Z | End of string, ignores m flag |
| \b | Word boundary |
| \B | Non-word boundary |
| \G | Start of match |
| \(?=...\) | Positive lookahead |
| \(?!...\) | Negative lookahead |
| \(?&lt;=...\) | Positive lookbehind |
| \(?&lt;!...\) | Negative lookbehind |
| \(?\(\)\|\) | Conditional |

## Regular Expression Flags

| **Character** | **Explanation** |
| :--- | :--- |
| i | Ignore case |
| m | ^ and $ match start and end of line |
| s | . matches newline as well |
| x | Allow spaces and comments |
| J | Duplicate group names allowed |
| U | Ungreedy quantifiers |
| \(?iLmsux\) | Set flags within regex |

## Regular Expression Special Characters 

| **Character** | **Explanation** |
| :--- | :--- |
| \n | Newline |
| \r | Carriage return |
| \t | Tab |
| \0 | Null character |
| \YYY | Octal character YYY |
| \xYY | Hexadecimal character YY |
| \x{YY} | Hexadecimeal character YY |
| \cY | Control character Y |

## Regular Expression Posix Classes

| **Character** | **Explanation** |
| :--- | :--- |
| \[:alnum:\] | Letters and digits |
| \[:alpha:\] | Letters |
| \[:ascii:\] | Ascii codes 0 - 127 |
| \[:blank:\] | Space or tab only |
| \[:cntrl:\] | Control characters |
| \[:digit:\] | Decimal digits |
| \[:graph:\] | Visible characters, except space |
| \[:lower:\] | Lowercase letters |
| \[:print:\] | Visible characters |
| \[:punct:\] | Visible punctuation characters |
| \[:space:\] | Whitespace |
| \[:upper:\] | Uppercase letters |
| \[:word:\] | Word characters |
| \[:xdigit:\] | Hexadecimal digits |

