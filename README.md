# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

if Graph1 = (V1, E1) and Graph2 = (V2, E2). if both graphs are complete and contain the same number of vertices meaning |V1| = |V2| = n. Since they are of equal size there must exist a bijection f : V1 -> V2 meaning each vertex in V1 is one to one and onto V2. We can prove this by laveling the vertices V1 as x1, x2...xn and graph two vertices in V2 as y1, y2...yn and defining f(xk) = yk for all k = 1,2...n. Because both graphs are complete graphs every pair of vertices in each graph is connected by an edge. that is for all u,v ∈ G1, the edge (u,v) ∈ E1 and similarly for all distinct f(u), f(v) ∈ V2, (f(u), f(v)), f(v)) ∈ E2. Since f maps vertices of G1 to vertices of G2 and preserve all pairwise connections because they are complete graphs you can conclude that adjacency is preserved in both directions. Thus for every edge (u,v) ∈ E1 the corresponding edge (f(u),f(v)) ∈ E2. and conversely, for every edge (f(u), f(v) ∈ E2, the pre-image (u,v) ∈ E1. this makes the graph isomorphic since it is a bijection.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
