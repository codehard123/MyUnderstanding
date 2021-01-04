Compilation process phases:-

Broad Definition :- Compiler is a program that convert a code from a high level language to a lowlevel (machine code) language
Types of Cmpiler :-
Single Pass Compiler :- Goes through the program single time
Multi pass compiler :- Goes through program multiple times

Phases of comilation:-
Two phases Syntheis phase and analysis phase :-

analysis phase:- From source program to intermediate code generation

Synthesis phase:- From Intemediate code generation to a target programm

Intermediate Code Generation is very close to the compiler

More Specific - Compiler converts the program from

Cousins of a compiler(indicated by &) :-
Source program----- written in high level language. Removes
&Preprocessor ------- handles preprocessor directive and does macro expansion... Also does target program generation

The output of preprocessor is modified source program which moves into the Compiler

&Compiler:--------- Compiler converts code from modified source program to assembly code...

&Assembler :- Assembly Code-> Relocatable Machine code(which does not have any memory address)

&(Loader/Linker)----- Loader takes the program(in all its entirety) and takes it into memory for execution(ie loads relocatable machine code into main memory) and Linker---- all other libraries are linked together with the program.....

Lexical ANalyzer
& Lexical Analyzer:- Extracts token from the code . Removes whitespaces and does micro expansion and file inclusion

& Syntax analyzer :- Verifies syntactically

& Semantic Analyzer :- Finds whether the given

Symbol Table Manager:-- Stores tokens and attributes. Scans and enters tokens into symbol table.
Error Handler:- Does error handlng and if cannot handle --- terminate compilation process

Phases of a compiler-
...................Analysis Phase....................

1. Lexical Analysis ---- Generates tokens/lexemes ... Removes whitespaces and comments also does file inclusion
   Lex tools --- Used for tokenization

2. Syntax analyzer:- Code follows syntax or not... Generates parse trees for validation

3. Semantic Analyzer:- Meaning correct or not(semantic verification) used parse trees to check if statement is meaningful or not

4. Intermediate COde Generation:- 3 address code ie at max 3 operands will be used.......to show elementary operations

5.

..............Synthesis Phase................... 5. Code Optimization:- Remove unreachable code

1. Lexical Analysis ---- Generates tokens/lexemes ... Removes whitespaces and comments also does file inclusion
   Lex tools --- Used for tokenization and
