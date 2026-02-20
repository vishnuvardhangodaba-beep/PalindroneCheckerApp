Palindrome Checker App – UC3
Reverse String Based Palindrome Check
Objective
The objective of this application is to validate whether a given string is a palindrome by reversing the string and comparing it with the original value.
This use case strengthens core Java fundamentals such as loops, string handling, and object comparison.
Use Case 3: Palindrome Check Using String Reverse
Goal
Check whether a string is a palindrome by:
Reversing the string using a loop
Comparing the original string with the reversed string
Displaying the result
Application Flow
Accept input from the command line.
Iterate through the string from the last character to the first.

Build a reversed string using concatenation.

Compare original and reversed strings using equals().

Display whether the string is a palindrome or not.

Key Concepts Used
For Loop
Used to iterate through the characters of the string in reverse order.

String Immutability
In Java, String objects are immutable. Every modification creates a new String object.

String Concatenation (+)
Used to build the reversed string character by character.

equals() Method
Used to compare the actual content of two strings instead of memory references.

Data Structure Used
String

How to Compile and Run
Step 1: Compile the Program
javac UseCase3PalindromeCheckerApp.java

Step 2: Run the Program
java UseCase3PalindromeCheckerApp madam

Example Outputs
Example 1
Command:
java UseCase3PalindromeCheckerApp madam

Output:
madam is a Palindrome.

Example 2
Command:
java UseCase3PalindromeCheckerApp hello

Output:
hello is NOT a Palindrome.

Project Structure
UseCase3PalindromeCheckerApp.java
README.md

Assumptions and Limitations
The program checks exact matches (case-sensitive).

Spaces and special characters are not ignored.

Only the first command-line argument is evaluated.

Learning Outcome
After completing this use case, you will understand:

How to iterate strings in reverse.

How string comparison works in Java.

The impact of string immutability.

Basic transformation-based validation techniques