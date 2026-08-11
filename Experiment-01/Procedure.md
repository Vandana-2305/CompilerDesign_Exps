Open a terminal and create a new FLEX file, symtab.l.
In the definitions section, include headers and declare the symbol table array along with insert()/lookup() helper functions.
In the rules section, define patterns for identifiers, constants, comments, and operators. Use { printf(...) } actions to print the recognized tokens and call insert() for identifiers. Save and compile the file using:
flex symtab.l
gcc lex.yy.c -o symtab -lfl Run the executable:
./symtab input.c
Observe the output and verify the tokens and symbol table entries
