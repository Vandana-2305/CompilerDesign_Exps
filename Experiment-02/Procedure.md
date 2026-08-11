Create a file with .l extension, lexer.l, where you write the FLEX code. 
Inside the file, define how to recognize tokens using regular expressions. 
Use the flex command to convert your .l file into a C program (lex.yy.c). 
Compile the generated C program using gcc to produce an executable.
Run the executable and give it input C code.
The output will show you which tokens were recognized (Keyword, Identifier, Number, Operator, Delimiter, etc.).
