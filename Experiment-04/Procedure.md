Create the FLEX file valvar.l using a text editor.
Define token patterns for letters and digits, and return them as LET and DIG tokens. Save and close the file.
Create the BISON file valvar.y.
Define grammar rules that recognize valid variable names (starting with a letter and followed by letters or digits). Save and close the BISON file.
Open terminal/command prompt and compile using:
o flex valvar.l
o bison -d valvar.y
o gcc lex.yy.c valvar.tab.c -o valvar -lfl Run the program: ./valvar
Enter test inputs like abc1, var123, 1abc to test validation. Observe whether the variable is valid or invalid.
