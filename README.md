# Palindrome
The input is a number. Determine if it is a palindrome. A number is a palindrome if read from right to left is equal to the original number.

Examples:

121 - palindrome

222 - palindrome

321 - not a palindrome

1212 - not a palindrome

12121 - palindrome

etc...

An important requirement: it is forbidden to convert the original number into a string and apply the reverse function to it. Verification is required by applying mathematical operations to the original number!

Hints:

number% 10 allows you to take the last digit

number * 10 allows you to add a digit to a number

number // 10 will cut off the last digit from the number

If the number is a palindrome print 'Palindrome' to the console, otherwise print 'No Palindrome'.
