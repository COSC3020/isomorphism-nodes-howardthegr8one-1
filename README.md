[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

# My Proof
Using a direct proof let's assume we have two graphs, $A$ and $B$, such that $A$ has 3 nodes and $B$ has only 2 nodes. If we were to create some mapping of $A$'s nodes to $B$'s nodes we would not be able to create an injective mapping as once we've mapped 2 of $A$'s nodes to the 2 nodes of $B$ there is still a node in $A$ that must be mapped but there's no available node in $B$ to do so. Thus we cannot create a bijective mapping since we can't even create an injective mapping of nodes, thus if two graphs do not have the same number of nodes they cannot be isomorphic. 
