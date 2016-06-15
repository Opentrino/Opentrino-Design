# Instruction Category: **Data Transfer**  

Instruction List:  
1. MOV  
2. SWAP  
3. PUSH  
4. PUSHA  
5. PUSHF  
6. POP  
7. POPA  
8. POPF  
_____  

# **MOV**
Meaning:  MOVe data from Source to Destination  
Format:  
Example:  

# **SWAP**
**Meaning**: Swaps 2 register's values  
Format:  
Example:  

# **PUSH**
**Meaning**: Pushes the Source operand into the stack and decrements ESP (stack pointer)  
Format:  
Example:  

# **PUSHA**
**Meaning**: Pushes all registers into the stack using the following order: EAX, ECX, EDX, EBX, ESP, EBP, ESI, EDI. ***Sidenote***: The value of ESP pushed is the value before the instruction is executed. It is useful for saving state before an operation that could potential change these registers  
Format:  
Example:  

# **PUSHF**
**Meaning**: Pushes the EFLAGS register content into the stack and decrements ESP  
Format:  
Example:  

# **POP**
**Meaning**: Fetches the value from the top of the stack, moves it into the operand specified and then increments ESP  
Format:  
Example:  

# **POPA**
**Meaning**: Fetches 8 32-bit values from the stack (which is the amount of available registers) in the order: EAX, ECX, EDX, EBX, ESP, EBP, ESI, EDI (notice the reverse order)  
Format:  
Example:  

# **POPF**
**Meaning**: Loads the top value of the stack and stores it into EFLAGs  
Format:  
Example:  
