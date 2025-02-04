# Symex-Vul_Detection
The WIMFGSymex project implements a symbolic execution engine for analyzing C programs to detect feasible execution paths and identify specific target conditions. By symbolically interpreting variables and expressions, this engine can simulate various code paths and determine the feasibility of conditional statements, loops, and assignments without actually running the code.

This implementation uses Python’s tree-sitter library to parse C code into an abstract syntax tree (AST), and the Z3 solver for Satisfiability Modulo Theories (SMT) to evaluate path conditions. This combination enables us to explore paths systematically, storing variable states symbolically, and verifying whether certain program states or outputs are achievable under specified conditions.
