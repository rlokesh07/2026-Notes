# EECS 370 Lecture 3 - LC2K Instruction Set

## Instructions Overview

- **add**  
  Syntax: `add regA regB destReg`  
  Adds the values in `regA` and `regB` and stores the result in `destReg`.

- **nor**  
  Performs bitwise NOR on two registers, same sign/fax as add.

- **lw (load word)**  
  Syntax: `lw regA regB offset`  
  Loads a word from memory at address `regA + offset` into `regB`.

- **sw (store word)**  
  Syntax: `sw regA regB offset`  
  Stores the value from `regB` into memory at address `regA + offset`.

- **beq (branch if equal)**  
  Syntax: `beq regA regB offset`  
  If the contents of `regA` and `regB` are equal, branch to `PC + offset`. The PC is incremented after the branch instruction regardless.

- **jalr (jump and link register)**  
  (Not detailed in notes)

- **halt**  
  Ends the program.

- **noop**  
  Does nothing (no operation).

## Examples

- `add 1 2 3`  
  Add contents of register 1 and register 2, store result in register 3.

- `lw 0 1 1000`  
  Load word from memory address `reg0 + 1000` into register 1.

- `sw 0 2 1000`  
  Store word from register 2 into memory address `reg0 + 1000`.

- `beq 1 2 7`  
  If register 1 equals register 2, branch to `PC + 7`.

## Notes

- The PC (program counter) increments after every instruction, including branches.
- The `nor` instruction performs bitwise NOR, useful for logical operations.
- `halt` ends the program execution.
- `noop` is used when no operation is needed for a cycle.

---

Source: https://www.industrydocuments.ucst.edu/docs/rlm0227