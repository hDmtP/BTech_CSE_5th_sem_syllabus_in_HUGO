---
title: "Compiler Design"
date: 2022-09-01T14:36:17+05:30
draft: false
---

[~/](../../)
[~/posts/](../)

### Objective

> To understand and list the different stages in the process of compilation.

> Identify different methods of lexical analysis

> Design top-down and bottom-up parsers

> Identify synthesized and inherited attributes

> Develop syntax directed translation schemes

> Develop algorithms to generate code for a target machine

----

1. **Introduction to Compiling**[ ]
    Compilers, Analysis of the source program, The
    phases of the compiler, Cousins of the compiler.

2. **Lexical Analysis**[ ]
    The role of the lexical analyzer, Tokens, Patterns,
    Lexemes, Input buffering, Specifications of a token,
    Recognition of a
    tokens, Finite automata, From a regular expression
    to an NFA, From a regular expression to NFA,
    From a regular expression to DFA, Design of a
    lexical analyzer generator (Lex)

3. **Syntax Analysis**[ ]
    The role of a parser, Context free grammars,
    Writing a grammar, Top down Parsing, Non-
    recursive Predictive parsing
    (LL), Bottom up parsing, Handles, Viable prefixes,
    Operator precedence parsing, LR parsers (SLR,
    LALR), Parser generators (YACC). Error Recovery
    strategies for different parsing techniques.

4. **Syntax directed translation**[ ]
    Syntax director definitions, Construction of syntax
    trees, Bottom-up evaluation of S attributed
    definitions, L attributed definitions, Bottom-up
    evaluation of inherited attributes.

5. **Type checking**[ ]
    Type systems, Specification of a simple type
    checker, Equivalence of type expressions, Type
    conversions

6. **Run time environments**[ ]
    Source language issues (Activation trees, Control
    stack, scope of declaration, Binding of names),
    Storage organization
    (Subdivision of run-time memory, Activation
    records), Storage allocation strategies, Parameter
    passing (call by value, call by reference, copy
    restore, call by name), Symbol tables, dynamic
    storage allocation techniques.

7. **Intermediate code generation**[ ]
    Intermediate languages, Graphical representation,
    Three-address code, Implementation of three
    address statements
    (Quadruples, Triples, Indirect triples).

8. **Code optimization**[ ]
    Introduction, Basic blocks & flow graphs,
    Transformation of basic blocks, Dag representation
    of basic blocks, The
    principle sources of optimization, Loops in flow
    graph, Peephole optimization.

9. **Code generations**[ ]
    Issues in the design of code generator, a simple
    code generator, Register allocation & assignment.