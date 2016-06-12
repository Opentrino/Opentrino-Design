# CPU Specifications

The Microprocessor will support multiple technologies that are present in large modern Microprocessors.

As it was already described in the main document (README.md), the high level goals for this project (Centrino Microprocessor) are:

**ISA:**
>1- **32 bit CISC** Architecture  
2- Influenced heavily by the **x86** instruction set and architecture in its entirety  
3- Support for all x86 instructions (**54**) and more  
4- **Memory Management Unit** support, and thus Paging

**Microarchitecture:**
1- Multiple **Pipelines** (the amount will is yet to be determined)  
2- A **Cache** mechanism (will require heavy research)  
3- Most of its functionality will contain **Microcode**
4- It must be **Superscalar**. One of the goals is to have a very fast **throughput**
5- **Branch Prediction** will also need to be implemented
6- In order to improve throughput, **VLIW** (Very Long Instruction Word) is within the plans.
7- To extend throughput even further, **Multithreading** will also be implemented
8- There is also plans to make the Microprocessor **Multi Cored**, however, this choice is not yet confirmed.
9- A **Floating Poing Unit** may also be implemented.
