# NP-Complete Universe — 8 Geometries of One Problem

One SAT formula. Eight NP-complete problems. Same answer, different geometry.

## [▶ Live Demo](https://aidoctrine.github.io/np-complete-universe/)

## What This Does

Toggle variable assignments and watch the same solution (or impossibility) 
appear simultaneously across eight representations:

| # | Problem | View | What You See |
|---|---------|------|-------------|
| ① | **SAT** | Logic | Clauses satisfied or not |
| ② | **Clique** | Graph density | k nodes, all connected |
| ③ | **Independent Set** | Graph sparsity | k nodes, none connected |
| ④ | **Vertex Cover** | Graph covering | Every edge touched |
| ⑤ | **3-Coloring** | Chromatic | T/F/B palette, valid coloring |
| ⑥ | **Hamiltonian Cycle** | Traversal | Cycle through all nodes |
| ⑦ | **Subset Sum** | Numeric | Digit matrix, column sums hit target |
| ⑧ | **Knapsack** | Optimization | Items, weights, values |

## Features

- **Auto-Solver**: Animated brute-force search with progress bar
- **UNSAT detection**: Watch ALL 2ⁿ assignments fail — NP-hardness made visible
- **Λ-meter**: Structural load from information theory (Λ·P ≤ C = ln 10)
- **n_crit ≈ 8**: Exponential wall threshold — predicted from sphere-packing geometry
- **Random formula generator**: Test with 3 to 8+ variables
- Zero dependencies, single HTML file, works offline

## The Point

NP-completeness means these eight problems are the **same problem** 
wearing different costumes. Every poly-time reduction is a change 
of coordinates, not a change of difficulty. Hardness is a property 
of the **space**, not the representation.

Or as we put it: *navigate, not compute*.

## Technical

- 28 KB, pure HTML/CSS/JS, no frameworks
- Hamiltonian Cycle: backtracking (≤14 nodes)
- Lambda: exact enumeration (≤16 variables)
- All reductions are constructive polynomial-time algorithms

## References

- Novgorodtsev, A. (2026). *The Geometry of Complexity*. Submitted to Entropy.
- Garey, M.R. & Johnson, D.S. (1979). *Computers and Intractability*.
- Karp, R.M. (1972). Reducibility among combinatorial problems.

## License

MIT
