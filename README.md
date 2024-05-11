Title: Assembly Input String and Uppercase Converter

Description:
This assembly code takes input from the user until they press Enter (ASCII 13) and converts the input string to uppercase characters. It uses DOS interrupts for input/output operations.

Usage:
1. Run the program.
2. Type your desired string.
3. Press Enter to convert the input string to uppercase.
4. The uppercase string will be displayed.

Code Structure:
- `.model small` specifies the memory model.
- `.stack 100h` reserves 256 bytes for the stack.
- `.data` declares the data section.
- `.code` declares the code section.
- `inputString proc` defines the procedure for input and conversion.
- `printString` label handles printing the uppercase string.
- `inputString endp` marks the end of the procedure.

How to Run:
1. Assemble the code using an assembler like MASM.
2. Link the object file.
3. Execute the generated executable file.


