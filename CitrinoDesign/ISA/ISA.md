# ISA - Instruction Set Architecture
- Architecture type: x86 CISC (32 bits only)

# **Instruction Set Table:**
|No.| Data Transfer | Arithmetic-Logic | Control | Bit Functions | I/O | String Functions | Flag Control | Misc | Special (x86)
|---|----------------|------------------|---------|---------------|-----|------------------|--------------|------|---------------|
|1|MOV|ADD|JMP|BT|IN|MOVS|STF|NOP|LGDT
|2|PUSH|SUB|JCO|BTS|OUT|CMPS|CLF|LEA|LIDT
|3|PUSHA|MUL|CALL|BTR|INS|LODS|LAHF|CPUID
|4|PUSHF|DIV|RET|BTC|OUTS|STOS|SAHF
|5|POP|INC|IRET|SET||SETS|STI
|6|POPA|DEC|INT|SETC||REP|CLI
|7|POPF|NEG|LOOP|TEST||REPC
|8|SWAP|CMP|HLT
|9||AND|WAIT
|10||OR
|11||XOR
|12||NOT
|13||NAND
|14||SAL
|15||SAR
|16||ROR
|17||ROL

(The table will be under constant alteration)

# **Registers**
[Consult this page for the registers' specification](https://github.com/Opentrino/Opentrino-Design/blob/master/CitrinoDesign/ISA/Registers.md)

# **Addressing Modes**
The following image summarises the addressing modes that are being planned for implementation:
![Adressing Modes](http://www.electronics.dit.ie/staff/tscarff/8086_address_modes/8086_address_modes.gif)  
