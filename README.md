# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If Graph1 = (V1, E1) and Graph2 = (V2, E2) are both complete and have the same number of vertices, then |V1| = |V2| = n, so there exists a bijection f from V1 to V2. Since both graphs are complete, every pair of distinct vertices in V1 is connected by an edge, and the same holds for V2. Therefore, for any edge (u, v) in E1, (f(u), f(v)) will be in E2, and vice versa. This shows that f preserves adjacency in both directions, so the graphs are isomorphic. We know such a bijection exists because bijections, by definition, match each element in V1 to a unique element in V2 when the sets have equal size.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
