# lab-task-2
The code reads a C/C++ source code file, processes each line, and identifies and 
classifies keywords, operators, numbers, and valid identifiers using various functions. However, 
there is a mistake in the conversion of the string to a C-style string in the main function, and it 
should be corrected for the program to work as intended.

Moreover
Token Classification Functions:
isPunctuator(char ch): Checks if a character is a punctuator (e.g., space, arithmetic operators, 
parentheses, etc.).
validIdentifier(char* str): Determines if a given string is a valid identifier by checking its first 
character and subsequent characters for punctuators.
isOperator(char ch): Identifies whether a character is an operator.
isKeyword(char* str): Checks if a given string matches known C++ keywords.
Lexical Analysis:
isNumber(char* str): Identifies if a string is a valid number.
subString(char* realStr, int l, int r): Extracts a substring from a given string.
