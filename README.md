# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

///
Assuming g1g2 is isomorphic, then there exists f: v1 -> v2, and it needs to satisfy that the node in v1 can be mapped to the only node in v2, and each node in v2 must be mapped by a node in v1.

So it needs to satisfy f: |v1| = |v2|. If the number of nodes matches, there is no bijection, and g1g2 is not isomorphic.

In simple terms, assuming g1 has n nodes and g2 has k nodes, if n != k, then they cannot be paired, indicating that they are not isomorphic.

###
https://en.wikipedia.org/wiki/Isomorphism
https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#what-is-graph-isomorphism
https://en.wikipedia.org/wiki/Bijection

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
