# Theory of Computing: Interactive Practice Solutions

Interactive, step-by-step practice solutions for a Theory of Computing course.

Prepared by **Md Nazrul Islam [NI]**, Lecturer, Dept. of CSE, Southeast University.

Open `index.html` through GitHub Pages (see the website link in the About box of this repository).

## Finite automata and regular languages

- `01-dfa-design.html`: **Design of Deterministic Finite Automata**. 25 DFA design problems built step by step, with an animated string simulator and a verifier.
- `02-nfa-design.html`: **Design of Nondeterministic Finite Automata**. 15 NFA problems with set-of-states simulation and every computation path drawn.
- `03-epsilon-removal.html`: **Epsilon Transitions and Their Removal**. ε-closures and cell-by-cell ε-removal for machines M1, M2, M3.
- `04-thompson-construction.html`: **Regular Expression to ε-NFA (Thompson Construction)**. Build an ε-NFA operator by operator from any regular expression, with parse tree and state count.
- `05-subset-construction.html`: **NFA to DFA by Subset Construction**. Watch the work list and transition table grow as an NFA becomes a DFA.
- `06-dfa-minimization.html`: **DFA Minimization by the Partition Method**. Round-by-round block splitting with signature tables and a pair tester.
- `07-dfa-to-regex.html`: **DFA to Regular Expression (R Method)**. The Rᵏᵢⱼ tables level by level, with every entry checked against the machine.
- `08-formal-definitions.html`: **Formal Definitions and the Extended Transition Function**. The 5-tuple, δ̂ expansion, an induction proof and the pigeonhole argument.

## Context-free languages, pushdown automata and Turing machines

- `09-chomsky-hierarchy.html`: **Classification of a Grammar in the Chomsky Hierarchy**. Production-by-production checks for Types 0–3 with derivations.
- `10-cfg-design.html`: **Design of Context-Free Grammars**. 15 grammar design problems with derivations, parse trees and a verifier.
- `11-derivations-parse-trees.html`: **Leftmost and Rightmost Derivations, Parse Trees**. Both derivations side by side with the parse tree growing step by step.
- `12-ambiguity.html`: **Ambiguity of a Grammar**. Two distinct parse trees for every ambiguous grammar, and why the others are unambiguous.
- `13-useless-symbols.html`: **Elimination of Useless Symbols**. Generating and reachable symbols round by round, and why the order matters.
- `14-epsilon-productions.html`: **Elimination of Epsilon Productions**. Nullable symbols and every keep-or-leave-out choice listed.
- `15-unit-productions.html`: **Elimination of Unit Productions**. Unit pairs with the reason each was added, then the new grammar.
- `16-chomsky-normal-form.html`: **Conversion to Chomsky Normal Form**. The full five-step pipeline, with the grammar after each step and a CYK table.
- `17-pda-design.html`: **Design of Pushdown Automata**. Animated stack simulator for 13 PDAs with instantaneous descriptions.
- `18-cfg-to-pda.html`: **Construction of a PDA from a Context-Free Grammar**. The one-state construction, with the stack tracing a leftmost derivation.
- `19-turing-machines.html`: **Design of Turing Machines**. Ten Turing machines with a scrolling tape simulator and full transition tables.

## Supplements

- `20-regex-simplification.html`: **Simplification of Regular Expressions: Laws and Practice**. 20 algebraic laws, 15 practice problems with a checker, and an automatic simplifier.
- `21-p-np-complexity.html`: **P, NP and NP-Completeness in Simple Terms**. Growth charts, a certificate game, reductions, SAT, 3-colouring and 13 application problems.
- `22-toc-applications.html`: **Theory of Computation in the Real World**. Metro ticket machine, Sudoku, compilers, search, parsing, TCP, halting problem and more.
- `23-coding-the-machines.html`: **Coding the Machines in Python**. DFA, NFA, ε-NFA, CFG, CNF/CYK, PDA and Turing machine, run line by line.

## Using the pages

- Every page is a single self-contained HTML file; no installation is needed.
- Every page starts with a Concept section: what the topic means, what it does, its formal definition, a runnable diagram, practical examples, key terms and common mix-ups.
- Each page works on a projector (white background) and can be printed or saved as PDF with the Print button.
- Keyboard: ← and → change problem, Space advances most simulators.

## Copyright

© 2026 Md Nazrul Islam [NI]. All rights reserved. Shared with students for study purposes only. Do not modify, republish or redistribute without the author's permission.
