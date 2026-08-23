# Experiment 10: Procedure

## PROCEDURE:

Create the FLEX file `backend.l` to tokenize identifiers and operators from TAC lines.

Create the BISON file `backend.y` with a grammar for TAC assignment statements, embedding 8086 `MOV`/`ADD`/`SUB`/`MUL`/`DIV` instruction generation directly in the semantic actions.

Compile and run:

```bash
flex backend.l
bison -d backend.y
gcc lex.yy.c backend.tab.c -o backend -lfl
./backend
