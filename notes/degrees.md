# The degree of a vertex, and regular graphs

## Reading

- Read 2.1, pages 31-36
    - What is the **degree** of a vertex in a graph?
        - What range of values can the degree of a vertex possibly take?
        - What vertices do we call **leaves**?
    - What is the **neighborhood** of a vertex? Does a vertex belong to its neighborhood?
        - Can two vertices have the same neighborhood?
    - What is the **minimum degree** and the **maximum degree** of a graph $G$?
        - True or False: A graph $G$ with minimum degree $0$ must be disconnected.
        - True or False: A graph $G$ with maximum degree equal to the largest allowable value must be connected.
        - True or False: In every graph of order at least $3$, the minimum degree $\delta(G)$ must be strictly smaller than the maximum degree $\Delta(G)$.
    - State and prove the **First Theorem of Graph Theory**.
        - Think about and state an improved theorem for the case of a bipartite graph.
    - After reading through example 2.2, do exercise 2.3.
    - Prove corollary 2.3: Every graph has an even number of "odd" vertices.
    - Prove theorem 2.4: If $G$ is a graph of order $n$ where $\textrm{deg}(u) + \textrm{deg}(v) \geq n-1$ for any non-adjacent vertices, then $G$ is connected with diameter $\leq 2$ (This is basically an application of the pigeonhole principle).
        - Prove the corollary 2.5 of this theorem: If $\delta(G)\geq (n-1)/2$ then $G$ is connected.
        - Show by an example that the bound is sharp: There are graphs with $\delta(G)$ equal to the first integer before $(n-1)/2$ that are disconnected.
        - How does the sum of all the in-degrees in a digraph compare to the sum of all the out-degrees?
    - Practice problems: 2.1, 2.2, 2.5, 2.6, 2.9, 2.16
- Read 2.2, pages 38-41
    - When is a graph called a **regular** graph?
    - Describe the **Petersen** graph.
    - Explain why we can't have a regular graph of odd order and odd degree.
    - True or False: A graph $G$ is regular if and only if its complement $\bar G$ is regular.
    - Describe the **Harary graphs** $H_{r, n}$ for $r\leq n-1$ and where not both $r$ and $n$ are odd. The construction is different depending on whether $r$ is odd or even.
        - Draw graphs of $H_{3,8}$ and $H_{4,9}$, using Figure 2.9 as a guide.
    - Prove theorem 2.7: For every graph $G$ and every $r\geq \Delta(G)$ there exists an $r$-regular graph $H$ that contains $G$ as an *induced* subgraph.
        - Make sure to clearly understand the construction involved.
        - Illustrate the construction starting with $P_3$ and using $r=2$ as well as $r=3$.
    - Practice problems: 2.19, 2.20, 2.29
