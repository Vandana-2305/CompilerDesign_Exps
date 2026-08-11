PROCEDURE:

Create the FLEX file tac.l:

    • Tokenize input using patterns for identifiers, numbers, and operators.
    • Pass tokens to BISON.

Create the BISON file tac.y:

    • Parse arithmetic expressions.
    • Generate three-address code using temporary variables (t1, t2, etc.) during parsing.

Compile and run:

    flex tac.l
    bison -d tac.y
    gcc tac.tab.c lex.yy.c -o tac -lfl
    ./tac

Input an arithmetic expression like:

    a = b + c * d

View the generated three-address code.
