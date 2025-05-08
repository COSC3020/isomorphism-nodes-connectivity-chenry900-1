# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

The definition of bijection is it must be one to one V1 = V2 and it must be onto every distinct v1 is hit by some v2 and that every node must be appear in the graph exactly once for each one.
If Graph1 = (V1,E1) and Graph2 = (V2,E2) are both someplete and have the same number of nodes
|V1| = |V2| = n. then the vertex sets have the same cardinality, there exists a bijection V1 -> V2.
this means that each vertex in V1 can be uniquely matched to a vetex in V2. Since the graphs are complete, each pair of distinct vertices in the graphs are connected by and edge. Thus for any pair (u,v) ∈ E1 where u,v ∈ V1 and u is not equal to v, then f(u) and f(v) are distinct vertices in V2, and because G2 is complete (f(u),f(v)) ∈ E2. So because f is a bijection, for every edge (f(u), f(v)) ∈ E2, U and V must be distinct vertices in V1, and since G1 is complete it must be (u,v) ∈ E1. thus the mapping of f preserves adjacency in both directions, and so it is isomorphic between G1 and G2.

I read cniemitalo's, aPannell064 and E-Merrill's saw what they did then went and looked at the slides and lecture videos as you have made it clear I cant copy anyone elses work. With your last comment I asked the TA what he thought you were asking for and he suggested you were asking for the definition of a bijection so I looked up the definition and wrote it. The work is my own.
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
