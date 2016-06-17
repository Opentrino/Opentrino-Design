# ISA - Instruction Set Architecture
**ISA Definition:** The interface of a Microprocessor design that is exposed to the Programmer/Compiler.

- Architecture type: x86 CISC (32 bits only)
- x86 CISC main features:
  - Complex Instructions (compared to RISC)
  - Variable Length Instruction
  - Non-Uniform Decoder
  - Many Addressing Modes (see below)

# **Instruction Set Table:**
|No.| [Data Transfer](https://github.com/Opentrino/Opentrino-Design/blob/master/CitrinoDesign/ISA/Instructions/DataTransfer.md) | Arithmetic-Logic | Control | Bit Functions | I/O | String Functions | Flag Control | Misc | Special (x86)
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

# **Flags**

# **Addressing Modes**
The following image summarises the addressing modes that are being planned for implementation:
![Adressing Modes](http://www.electronics.dit.ie/staff/tscarff/8086_address_modes/8086_address_modes.gif)  

**Note**: Not all instructions support all these addressing modes. Consult the instruction page in order to know what kind of addressing modes a certain instruction will support. 

# **Data Types**

# **Interrupts and Exception Handling**

# **I/O**

# **Memory Organization / Hierarchy**
