# Experiment 9: Procedure

## PROCEDURE:

Create the FLEX file `optimize.l` to tokenize identifiers, numbers, and the operators `+`, `-`, `*`, `/`, `=`, and `;`.

Create the BISON file `optimize.y` with a grammar for assignment statements and expressions.

In the semantic actions for each `expr` rule, check whether constant folding, strength reduction, or algebraic simplification applies, and print a comment indicating which optimization fired.

Compile using:

```bash
flex optimize.l
bison -d optimize.y
gcc lex.yy.c optimize.tab.c -o optimize -lfl
