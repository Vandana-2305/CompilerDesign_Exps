START

1. Create a FLEX file to recognize:
      • int
      • float
      • identifiers
      • numbers
      • operators

2. Return the recognized tokens from FLEX to BISON.

3. Create a BISON file and define grammar rules for:
      • Variable declarations
      • Assignment statements
      • Expressions

4. Initialize a symbol table to store:
      • Variable name
      • Variable type

5. When a declaration is encountered:
      Insert the variable name and its type into the symbol table.

6. When an assignment statement is encountered:
      Look up the type of the destination variable.

7. Check the types of the variables used in the expression.

8. If a variable is not present in the symbol table:
      Display "Undefined variable".

9. If the types of the operands and result match:
      Display "No type mismatch".

10. Otherwise:
      Display "Type mismatch".

11. Continue processing the input statements.

12. Stop when all statements have been processed.

STOP
