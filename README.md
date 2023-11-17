# Top-C

#currently a lexer and parser has been made.

Lexer tokenizes the characters input in terminal.
It can distinguish between INTs,Floats,Arithmetic operations, and parantheses.

These tokens are then read by parser to "understand" the character.
Parser right now is capable of identifying basic arithmetic operations, Terms, Expressions and Factors.
Using Terms,Expressions and Factors, Parser can identify the sequence of operations as well: establishing BODMAS rules
