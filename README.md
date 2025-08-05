# Compare-First-N-Last-N-characters

Question Explanation:

The task is to write a program that reads a string and a number N, and then checks whether the first N characters of the string are different from the last N characters of the string.

Logical Approach:

Read Inputs:
Read the input string.
Read the integer N.

Extract First and Last N Characters:
Extract the first N characters from the beginning of the string.
Extract the last N characters from the end of the string.

Compare the Extracted Characters:
Compare the first N characters with the last N characters.
If they are not the same, the result is True. Otherwise, it is False.

Output:
Print the result of the comparison.

Example for Clarity:

If the string is toronto and N = 2:
The first 2 characters are to.
The last 2 characters are also to.
Since the first 2 and the last 2 characters are the same, the output is False.
If the string is educated and N = 3:
The first 3 characters are edu.
The last 3 characters are ted.
Since edu is not the same as ted, the output is True.
