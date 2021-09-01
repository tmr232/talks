# Implementing C++ Semantics in Python

**Presented:** 2021-08-26

## Abstract

Coding in Python, I often find myself reaching for C++ features and techniques.

Deterministic destructors and RAII, for example, are wonderful C++ constructs with no true equivalent in Python (or most any Garbage Collected language, for  that matter).

The semantics around object lifetimes are just too different.

But what if we could bring C++’s destructors into Python? What if we could bring more semantics?

In this talk I will present a library that does exactly that. We will  bring destructors, function overloading, member access specifiers, and  more into Python. You will see the implementation of each feature, and  all the dirty tricks used to make them work.

By replicating parts of C++ in Python, we will also gain a better understanding of C++’s  semantics and the interactions between different language features.

Existing Python knowledge is not required; we will cover all the relevant syntax and semantics during the talk.

## Content

- [Slides]
- [Code]





[Slides]:slides.pdf
[Code]:https://github.com/tmr232/cpppy
