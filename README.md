# Haskell Lazy Evaluation Bug

This repository demonstrates a common pitfall in Haskell programming related to lazy evaluation and infinite data structures. The code in `bug.hs` contains a function that can generate an infinite list, leading to a program that never terminates when that list is processed.

The solution, found in `bugSolution.hs`, addresses this issue by implementing a check to prevent the generation of the infinite list.