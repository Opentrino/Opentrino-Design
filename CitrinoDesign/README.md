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
8- There are also plans to make the Microprocessor **Multi Cored**, however, this choice is not yet confirmed  
9- A **Floating Poing Unit** will also be implemented

___
___
___
# **Microprocessor Specifications (overview):**  

# **> ISA < ([Complete ISA Specs](https://github.com/Opentrino/Opentrino-Design/blob/master/CitrinoDesign/ISA/ISA.md))**  

# 1.1. Architecture of choice  

# 1.2. Instructions (types and formats)  

# 1.3. Data Types

# 1.4. Memory Addressing Modes

# 1.5. Registers

# 1.6. Flags

# 1.7. Interrupts and Exception Handling

# 1.8. Access Control and Prioritization/Privilege

# 1.9. Global Modes of Execution

# 1.10. I/O 
    Memory Mapped IO
    External IOCTL

# 1.11. Memory Organization / Hierarchy
    DRAM / SDRAM / SRAM
    Virtual Memory (MMU)
    Direct Memory Access (DMA)
    Caches (refer to Microarchitecture section)
    LUTs/ROM (Microcode)
    
# 1.12. Task and Thread controller/manager

# 1.13. Multithread and Multicore support

# 1.14. Power Manager
    ACPI

___
# **> Microarchitecture < ([Complete Microarchitecture Specs](https://github.com/Opentrino/Opentrino-Design/blob/master/CitrinoDesign/Microarchitecture/Microarchitecture.md))**

# 2.1. Pipelines

# 2.2. External Interfacing / IO
     Bus Logic
     Dataflow Algorithms (Northbridge/Southbridge-like)

# 2.3. Control Unit
     FSM Logic
    
# 2.4. Memory Controller
    Memory Access mechanism (scheduling policy)

# 2.5. Execution **Algorithms**
    Speculative Execution
    Branch Prediction
    
# 2.6. Superscalar Processing

# 2.7. Caches
     Level
     Size
     Caching Algorithms

# 2.8. Instruction Execution Cycle
     Prefetching and Fetching
     
# 2.9. Flexibility of design
     Voltage scaling
     Clock scaling / multiplier
     
# 2.10. Error correction

# **> Engineering Factors <**

# 3.1. Expected throughput / Performance
  
# 3.2. Optimizations and Efficiency

# 3.3. Compatibility

# 3.4. Extensibility

# 3.5. Flexibility

___
# **> Engineering Standards <**  

___
# **> Research Resources <**

**Books/Textbooks:**  
1- [Computer Organization and Design: The Hardware/Software Interface - by David A. Patterson,  John L. Hennessy ](https://www.amazon.co.uk/Computer-Organization-Design-Interface-Architecture/dp/0124077269/ref=sr_1_2?ie=UTF8&qid=1465867988&sr=8-2&keywords=computer+organization+and+design)  

2- [Computer Organization and Design: The Hardware/Software Interface: ARM Edition - by David A. Patterson,  John L. Hennessy](https://www.amazon.co.uk/gp/product/0128017333/ref=ox_sc_act_title_2?ie=UTF8&psc=1&smid=A3P5ROKL5A1OLE)  

3- [Computer Architecture - A Quantitative Approach - by John Hennessy](https://www.amazon.co.uk/Computer-Architecture-Morgan-Kaufmann-Design/dp/012383872X/ref=sr_1_1?ie=UTF8&qid=1465868130&sr=8-1&keywords=computer+architecture+a+quantitative+approach)  

4- [Computer Organization and Architecture - by William Stallings](https://www.amazon.co.uk/Computer-Organization-Architecture-William-Stallings/dp/1292096853/ref=sr_1_6?s=books&ie=UTF8&qid=1472996956&sr=1-6&keywords=computer+architecture)

5- [Structured Computer Organization - by Andrew S Tanenbaum, Todd Austin](https://www.amazon.co.uk/Structured-Computer-Organization-International-Tanenbaum/dp/0273769243/ref=sr_1_1?s=books&ie=UTF8&qid=1472996867&sr=1-1&keywords=Structured+Computer+Organization)

6- [Inside the Machine: An Illustrated Introduction to Microprocessors and Computer Architecture - by Jon Stokes](https://www.amazon.co.uk/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680/ref=sr_1_1?s=books&ie=UTF8&qid=1472996766&sr=1-1&keywords=inside+the+machine)

7- [Modern Processor Design: Fundamentals of Superscalar Processors - by John P. Shen ](https://www.amazon.co.uk/Modern-Processor-Design-Fundamentals-Superscalar/dp/0070570647/ref=sr_1_1?ie=UTF8&qid=1465868200&sr=8-1&keywords=modern+processor+design+fundamentals+of+superscalar+processors)  

8- [Microprocessor Architecture: From Simple Pipelines to Chip Multiprocessors - by Jean-Loup Baer](https://www.amazon.co.uk/Microprocessor-Architecture-Simple-Pipelines-Multiprocessors/dp/0521769922/ref=sr_1_8?s=books&ie=UTF8&qid=1472996604&sr=1-8&keywords=microprocessor+architecture)

9- [Microprocessor Design: A Practical Guide from Design Planning to Manufacturing - by Grant Mcfarland](https://www.amazon.co.uk/Microprocessor-Design-Manufacturing-Professional-Engineering/dp/0071459510/ref=sr_1_1?ie=UTF8&qid=1465868255&sr=8-1&keywords=Microprocessor+design+a+practical+guide)  

10- [Embedded Computing: A VLIW Approach to Architecture, Compilers and Tools - by Joseph A. Fisher, Paolo Faraboschi, Cliff Young](https://www.amazon.co.uk/Embedded-Computing-Approach-Architecture-Compilers/dp/1493303651/ref=sr_1_3?s=books&ie=UTF8&qid=1472996676&sr=1-3&keywords=embedded+computing)

11- [Complete Digital Design: A Comprehensive Guide to Digital Electronics and Computer System Architecture - by Mark Balch](https://www.amazon.co.uk/Complete-Digital-Design-Comprehensive-Architecture-ebook/dp/B000THOD3Y/ref=sr_1_3?ie=UTF8&qid=1465868307&sr=8-3&keywords=Complete+digital+design)  

12- [OpenSPARC Internals - by David Weaver](https://www.amazon.co.uk/OpenSPARC-Internals-David-Weaver/dp/0557019745/ref=sr_1_1?s=books&ie=UTF8&qid=1472996806&sr=1-1&keywords=opensparc)

**Manuals:**  
1- [Intel® 64 and IA-32 Architectures Software Developer’s Manual - by Intel](http://www.intel.com/content/dam/www/public/us/en/documents/manuals/64-ia-32-architectures-software-developer-manual-325462.pdf)

**Cheat Sheets:**  
1- x86 ISA: [Part 1](http://www.jegerlehner.ch/intel/IntelCodeTablePreview-1.gif) | [Part 2](http://www.jegerlehner.ch/intel/IntelCodeTablePreview-2.gif)  
