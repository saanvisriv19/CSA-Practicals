Practical 3:
AIM: To write an assembly program that reads two numbers entered by the user, adds them and displays the sum.
Tool: CPU Sim 4.0.11 (Java 8 with JavaFX)
Observation: With inputs 25 and 17 the final registers are AC = 42, DR = 25 (the operand read by ADD), PC = 7, IR = 28673 (7001 hex = HLT) and E = 0, and memory holds A = 0019 hex and SUM = 002A hex. For −1 + 1 the result is 0
with E = 1 (carry out). For 30000 + 10000 the true sum 40000 does not fit in 16-bit two's complement, so the output is 40000 − 65536 = −25536 (overflow).
Result: The program correctly adds two user-entered numbers; 25 + 17 = 42.
