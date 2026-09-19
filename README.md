# Assembler
> Assembly language programs (AT&T syntax) written for a computer architecture laboratory course.

## Table of contents
* [General info](#general-info)
    * lab1/zad1
    * lab1/zad2
    * lab2
    * lab3
    * lab4
    * lab5
    * lab6
* [Setup](#setup)
* [Status](#status)
* [Contact](#contact)

## General info

* _lab1/zad1_ - `swap.s` reverses a fixed string in place, swapping the first character with the last, the second with the second-to-last, and so on,
* _lab1/zad2_ - `lower.s` converts all uppercase letters in a string to lowercase,
* _lab2_ - computes Fibonacci sequence values up to a given index (set via `NR_WYRAZU`), tracking even and odd indices separately in the `fib1` and `fib2` registers,
* _lab3_ - measures the time cost of declaring an `int` variable in C versus in an assembly function,
* _lab4_ - numerically integrates `f(x) = 2x + 4` over a given range and precision, storing the result in `%xmm0`,
* _lab5_ - extends lab4: the integration routine is called from a C `main.c` and timed with `my_cpuid`, comparing a plain `integrate(a, b, n)` against an SSE-optimized `integrate_sse(a, b, n)`,
* _lab6_ - measures cache access times.

## Setup
To run, for example, the lab3 project:

```
$ make my_cpuid
$ ./my_cpuid
```

## Status
**Archived** — not actively maintained.

Written in 2018 for a computer architecture lab course. Complete and working as submitted; kept here as a reference rather than for continued development.
