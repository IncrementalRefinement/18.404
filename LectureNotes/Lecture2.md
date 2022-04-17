
# Lecture2 Nondeterminism, Closure Properties, Conversion of Regular Expressions to FA

## Nondeterminism Finite Automata

New features

- multiple paths possible
- ε-transition
- accept input if **some** path leads to accept

Ways to think about nondeterminism:

**Computational**: Fork new parallel thread and accept if any thread leads to an accept state.
**Mathematical**: Tree with branches. Accept if any branch leads to an accept state.
**Magical**: Guess at each nondeterministic step which way to go. Machine always makes the right guess that leads to accepting, if possible

Every nondeterministic finite automaton has an equivalent deterministic finite automaton

## Closure under Concatenation&Star

Applying NFA, and easy

## Regular expression -> NFA

regular expression

A Regular Expression can be recursively defined by regular operation

the language of the regular expression, some regular expression corresponds to some language
