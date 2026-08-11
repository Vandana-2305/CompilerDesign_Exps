PROCEDURE:

Write the control.l file using FLEX to tokenize control structure keywords.

Write the control.y file using BISON to define grammar rules for C control structures.

Compile and execute the program using:

    flex control.l
    bison -d control.y
    gcc lex.yy.c control.tab.c -o control -lfl
    ./control

Input sample control structures in C-style syntax to check for validation.
