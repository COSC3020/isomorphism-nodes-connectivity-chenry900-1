# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If Graph1 = (V1,E1) and Graph2 = (V2,E2) are both someplete and have the same number of nodes
|V1| = |V2| = n. then the vertex sets have teh same cardinality, there exists a bijection V1 -> V2.
this means that each vertex in V1 can be uniquely matched to a vetex in V2. Since the graphs are complete, each pair of distinct vertices in the graphs are connected by and edge. Thus for any pair (u,v) ∈ E1 where u,v ∈ V1 and u is not equal to v, then f(u) and f(v) are distinct vertices in V2, and because G2 is complete (f(u),f(v)) ∈ E2. So because f is a bijection, for every edge (f(u), f(v)) ∈ E2, U and V must be distinct vertices in V1, and since G1 is complete it must be (u,v) ∈ E1. thus the mapping of f preserves adjacency in both directions, and so it is isomorphic between G1 and G2.

I looked at other peoples approved excersises and the slides then wrote my own.
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
