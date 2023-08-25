# Self-Project

Implementation of RISC-V base ISA, RV32I. 

Goal:
1. Comparison of different implementation (uArch) and its effects on performance, power comsumption, and area.
2. Reference material for learning computer architecture and chip design.
   The implementation will be documented with different levels of specification so people can challenge themselves and learn from it.
   For example, people can start from implementing the ISA and then add features such as pipelining, branch predictors, virtual memory, etc.
   Each different implementation will be documented with different level of details, giving guided challenges for students to learn.
    

General Design Questions of Implementation
1. Harvard Architecture or Von Neumann -
   Both architecture would be implemented to compare. Initially, Harvard Architecture will be implemented.
2. Choice of functional units - Ripple carry adder, carry-lookahead adder, or better adders or any computational units will be choosed and compared.
3. Number of pipelining - No pipelining, 3-stage pipelining, N-stage pipelining.
4. Branch Predictors - No branch predictors, saturating counter, novel ideas from research (research from Dr. Yale Patt from UT Austin).
5. PIM - Efforts to reduce the memory latency.
and more will be added in the future as I work on the project.

Currently in-progress. 

