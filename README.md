# RANDOM-PASSWORD-GENERATOR
Import Libraries:

random for generating random selections.
string for accessing predefined sets of characters (uppercase, lowercase, digits, punctuation).
Define generate_password Function:

Ensures the password length is at least 4 to include all character types.
Defines character sets (lower, upper, digits, special).
Ensures the password contains at least one character from each set.
Fills the remaining length with random choices from all character sets combined.
Shuffles the password list to ensure a random order.
Joins the list into a string and returns the password.
Define main Function:

Prompts the user for the desired password length.
Calls generate_password with the specified length.
Prints the generated password.
Execution Block:

Ensures the main function runs when the script is executed.
This script generates a random password with a good mix of different character types and ensures the password is sufficiently complex.






