# **CPU Goals**: to design a very fast and complete Microprocessor with modern features
___
# Microprocessor Features:

The Microprocessor will support multiple technologies that are present in large modern Microprocessors.

As it was already described in the main document (README.md), the high level goals for this project (Citrino Microprocessor) are:

**ISA:**  
1- **32 bit CISC** Architecture  
2- Influenced heavily by the **x86** instruction set and architecture in its entirety, including the registers  
3- Support for most x86 instructions  
4- **Memory Management Unit** support, and thus Paging

**Microarchitecture:**  
1- Multiple **Pipelines** (the amount is yet to be determined)  
2- A **Cache** mechanism (will require heavy research)  
3- Most of its functionality will contain **Microcode**  
4- It must be **Superscalar**. One of the goals is to have a **very fast throughput**  
5- **Branch Prediction** will also need to be implemented  
6- In order to improve throughput, **VLIW** (Very Long Instruction Word) is within the plans  
7- To extend throughput even further, **Multithreading** will also be implemented  
8- There is also plans to make the Microprocessor **Multi Cored**, however, this choice is not yet confirmed  
9- A **Floating Poing Unit** may also be implemented

___
___
___
# **Microprocessor Specifications:**  

# **> ISA <**
# Architecture of choice  

# Instructions (types and formats)  

# Data Types

# Memory Addressing Modes

# Registers

# Flags

# Interrupts and Exception Handling

# Access Control and Prioritization/Privilege

# Global Modes of Execution

# IO 
    Memory Mapped IO
    External IOCTL

# Memory Organization / Hierarchy
    DRAM / SDRAM / SRAM
    Virtual Memory (MMU)
    Direct Memory Access (DMA)
    Caches
    LUTs/ROM (Microcode)
    
# Task and Thread controller/manager

# Multithread and Multicore support

# Power Manager
    ACPI

___
# **> Microarchitecture <**

# Pipelines

# External Interfacing / IO
    Bus Logic

# Control Unit
    FSM Logic

# **> Engineering Factors <**

# Expected throughput / Performance
  

# Optimizations and Efficiency

# Compatibility

# Extensibility

___
# **> Engineering Standards <**  

___
# **> Research Resources <**

**Books/Textbooks:**  
1- [Computer Organization and Design: The Hardware/Software Interface - by David A. Patterson,  John L. Hennessy ](https://www.amazon.co.uk/Computer-Organization-Design-Interface-Architecture/dp/0124077269/ref=sr_1_2?ie=UTF8&qid=1465867988&sr=8-2&keywords=computer+organization+and+design)  

2- [Computer Architecture - A Quantitative Approach - by John Hennessy](https://www.amazon.co.uk/Computer-Architecture-Morgan-Kaufmann-Design/dp/012383872X/ref=sr_1_1?ie=UTF8&qid=1465868130&sr=8-1&keywords=computer+architecture+a+quantitative+approach)  

3- [Modern Processor Design: Fundamentals of Superscalar Processors - by John P. Shen ](https://www.amazon.co.uk/Modern-Processor-Design-Fundamentals-Superscalar/dp/0070570647/ref=sr_1_1?ie=UTF8&qid=1465868200&sr=8-1&keywords=modern+processor+design+fundamentals+of+superscalar+processors)  

4- [Microprocessor Design: A Practical Guide from Design Planning to Manufacturing - by Grant Mcfarland](https://www.amazon.co.uk/Microprocessor-Design-Manufacturing-Professional-Engineering/dp/0071459510/ref=sr_1_1?ie=UTF8&qid=1465868255&sr=8-1&keywords=Microprocessor+design+a+practical+guide)  

5- [Complete Digital Design: A Comprehensive Guide to Digital Electronics and Computer System Architecture - by Mark Balch](https://www.amazon.co.uk/Complete-Digital-Design-Comprehensive-Architecture-ebook/dp/B000THOD3Y/ref=sr_1_3?ie=UTF8&qid=1465868307&sr=8-3&keywords=Complete+digital+design)  

**Manuals:**  
1- [Intel® 64 and IA-32 Architectures Software Developer’s Manual - by Intel](http://www.intel.com/content/dam/www/public/us/en/documents/manuals/64-ia-32-architectures-software-developer-manual-325462.pdf)
