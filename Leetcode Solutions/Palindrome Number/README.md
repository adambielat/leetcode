# Palindrome Number<br>

<br><b>"Given an integer x, return true if x is a palindrome, and false otherwise."</b><br><br>

A palindrome is a word, phrase, or sequence that reads the same backwards as forwards, e.g. madam, 1551 or 2002.<br>
Therefore, we must return true if the integer given to us is the same forwards as reversed. We do this through reading the string from end to start with str(x)[::-1], and then comparing it to the original through ==str(x)
