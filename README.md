Racket-miniKanren
=================

Canonical miniKanren implementation in Racket.

Asumu Takikawa and Sam Tobin-Hochstadt cleaned up William E. Byrd's Super Chobo Racket code, which in turn was based on the Scheme implementation of miniKanren in the paper:

William E. Byrd, Eric Holk, and Daniel P. Friedman.
miniKanren, Live and Untagged: Quine Generation via Relational Interpreters (Programming Pearl).
To appear in the Proceedings of the 2012 Workshop on Scheme and Functional Programming, Copenhagen, Denmark, 2012.


CORE LANGUAGE

Logical operators:

==
fresh
conde

Interface operators:

run
run*


EXTENDED LANGUAGE

Constraint operators:

=/=
symbolo
numbero
absento
