# RNA Combinatorics

Computational aid for RNA combinatorics research

## Type C orbit generator.nb
This formatted Mathematica 11.0.1.0 notebook provides a visual demonstration of the concepts proven in [“RNA, local moves on plane trees, and transpositions on tableaux”](http://arxiv.org/abs/1411.3056) (Seegerer, Tripp, Tymoczko, and Wang).

When acting on the Young tableau representation of a set of RNA secondary structures, or “plane trees,” sharing the same number of edges, the Weyl group type C permutations split these planes trees into two self-contained orbits, one of symmetric plane trees and the other of asymmetric plane trees. The visualization aid summarizes the permutations, Young tableaux, plane trees, and orbits into a layered graph. Using Heitsch's theorem (http://people.math.gatech.edu/~heitsch/Pubs/plane.pdf), the notebook also includes functions that calculate the total number of plane trees, symmetric plane trees, and asymmetric plane trees given the number of edges of these plane trees. The notebook's functions are written in a way to allow for easy expansion for future projects. For example, we could use the visualization aid to see what happens if we apply Weyl group type D permutations to plane trees (even though doing so would fail to produce valid orbits).
