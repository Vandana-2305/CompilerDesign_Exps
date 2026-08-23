# Experiment 8: Procedure

## PROCEDURE:

### Create FLEX File (`typecheck.l`)

- Define patterns for keywords (`int`, `float`), identifiers, numbers, and operators.
- Return these tokens to BISON for further processing.

### Create BISON File (`typecheck.y`)

- Define grammar rules for declarations and expressions.
- Maintain a symbol table (array of name/type pairs) that is filled in on each declaration.
- On each assignment, verify that the operand types and result type match and print the outcome.

### Compile the FLEX and BISON Files

```bash
flex typecheck.l
bison -d typecheck.y
gcc lex.yy.c typecheck.tab.c -o typecheck -lfl
