## PSEUDOCODE:

START

1. Create a FLEX file to recognize identifiers and operators from the given three-address code.

2. Pass the recognized tokens from FLEX to BISON.

3. Create a BISON file with grammar rules for three-address code assignment statements.

4. Parse each TAC statement in the form:

      ID = expression ;

5. For the first operand:
      Generate `MOV AX, operand`.

6. For addition:
      Generate `ADD AX, operand`.

7. For subtraction:
      Generate `SUB AX, operand`.

8. For multiplication:
      Generate `MUL operand`.

9. For division:
      Generate:
          MOV DX, 0
          MOV BX, operand
          DIV BX

10. After processing the complete expression:
       Generate `MOV result, AX`.

11. Repeat the process for all TAC statements.

12. Display the generated 8086 assembly language instructions.

STOP
