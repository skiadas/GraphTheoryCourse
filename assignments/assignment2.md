# Assignment 2

1. Recall that $\delta(G)$ denotes the smallest degree of any vertex in $G$, and $\Delta(G)$ denotes the largest degree.
    a. Establish a relation between $\delta(\bar G)$ and $\Delta(G)$. This should be a formula that allows us to compute one from the other.
    b. Prove that if $G$ has order $n$, then $\delta(G) + \delta(\bar G) \leq n-1$.
    c. Prove that equality in the previous part holds if and only if $G$ is regular.
    d. Prove that a graph of order $n$ is regular if and only if there is a vertex $v$ such that its degree in $G$ is equal to $\delta(G)$ and its degree in $\bar G$ is equal to $\delta(\bar G)$.
2. We want to find all non-isomorphic *connected* graphs of order $5$ and size $6$.
    a. First determine all possible degree sequences for such graphs. You should find five possible degree sequences, four of which are graphical. Two of those have a vertex of degree $4$, and two have one or more vertices of degree $3$.
    b. Construct the two graphs corresponding to the degree sequences for the two sequences that have a vertex of degree $4$, and prove that there are no other such graphs (hint: there is only one way the vertex of degree $4$ can be added to a smaller graph to obtain the desired graph).
    c. From the two sequences that have only vertices of degree at most $3$, one has only one possible graph corresponding to it, and the other has two. You must find those graphs and prove that they are the only possibilities (hint: think of what vertices one of the degree-3 vertices can connect to).
    d. You should have found a total of five different graphs. Make sure to draw the graphs in as symmetric a way as possible. Also determine which of these graphs are bipartite.
