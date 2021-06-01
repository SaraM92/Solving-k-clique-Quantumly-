# Finding Small and Large k-Clique Instances on a Quantum Computer


This repository contains the code files for the paper [arXiv:2008.12525v1](https://arxiv.org/abs/2008.12525)

The paper discusses the practical implementation of the k-clique problem. The [k-clique problem](https://en.wikipedia.org/wiki/Clique_problem#:~:text=In%20the%20k%2Dclique%20problem,all%20cliques%20of%20size%20k.) is a famous graph problem where a set of nodes are given, and the algorithm is asked to find cliques of size k in the graph.

We addressed the problem using [Grover's algorithm](https://www.quantiki.org/wiki/grovers-search-algorithm) with two different oracle implementations and certain symmetric states preparation such as *W-states* and *Dicke-states*.

**This repository contains 6 Jupyternotbooks for the problem:**
1. Oracle implementation 1 over the entire search space.
1. Oracle implementation 1 with W-state preparation to limit search space.
1. Oracle implementation 1 Dicke-state preparation to limit search space.
1. Oracle implementation 2 over the entire search space.
1. Oracle implementation 2 with W-state preparation to limit search space.
1. Oracle implementation 2 Dicke-state preparation to limit search space.


In order to run the code correctly, you will need to have installed a working version of [Qiskit](https://qiskit.org/).
