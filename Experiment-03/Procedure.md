PROCEDURE:

Open a text editor and write the FLEX source file art_expr.l.

Define regular expressions for identifiers, digits, operators, and ignore whitespaces.

Save and close the FLEX file.

Open another text file and write the BISON source file art_expr.y.

Define tokens and grammar rules to parse arithmetic expressions using +, -, *, and /.

Save and close the BISON file.

Use the following commands to compile and run:

    flex art_expr.l
    bison -d art_expr.y
    gcc lex.yy.c art_expr.tab.c -o art_expr -lfl
    ./art_expr

Enter expressions as input. If the expression is valid, it displays "valid Expression", otherwise "Invalid Expression".
