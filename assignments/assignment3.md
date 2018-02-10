# Assignment 3

In this assignment we will find all non-isomorphic forests of order $6$. Recall that a forest is a graph whose connected components are trees.

1. As preliminary work for this, you should list all non-isomorphic trees of order up to $5$. You should find exactly one tree for orders $1$, $2$ and $3$, two trees for order $4$ and three trees for order $5$. Think of the possible degree sequences as a start.
2. Now we proceed to find all forests of order $6$ that are not trees. So they must have at least two connected components, and all those components will be amongst the trees you found in problem 1.
    a. There are a few easy extreme cases: There is exactly one forest with six components, and one forest with five components. Find them and explain why there aren't any more, up to isomorphism (hint: how many vertices would go to each component? There aren't that many possibilities).
    b. There are up to isomorphism exactly two forests consisting of four components. Find them and prove that they are the only ones.
    c. There are up to isomorphism exactly four forests consisting of three components. Find them and prove that they are the only ones (hint: in terms of number of vertices that go in each component, there are exactly three possibilities; one of those possibilities has two non-isomorphic graphs corresponding to it).
    d. Finally, we look at the forests with two components. You should be finding exactly six such non-isomorphic forests, divided into three categories depending on how many vertices each of the two components has.
3. Next we will find all trees of order $6$. You should be able to write down $5$ different possible degree sequences (theorem 4.3 helps narrow down the possibilities). Four of those have only one graph corresponding to them, while one of them has two non-isomorphic trees corresponding to it. You should end up with six possible non-isomorphic trees.
4. This problem continues from the work on the trees of order $6$. Recall from problem 3 that there are six such trees. In this problem we will try to determine what *automorphisms* these graphs have. Recall that an automorphism is an isomorphism from the graph to itself. So it amounts to a possible reshuffling of the vertices, but only in such a way as to maintain the edges. For example, a vertex of degree 1 can only go to a vertex of degree 1 under such a function. Also note that there is always at least one automorphism, namely the identity automorphism that sends each vertex to itself.
    a. One of the trees has a vertex of degree $5$. This tree has exactly $5!=120$ automorphisms. Describe those automorphisms.
    b. One of the trees is a path. This tree has exactly two automorphisms. Describe them and explain why they are the only ones.
    c. One of the trees has two vertices of degree $3$. This tree has exactly $2\times 2\times 2$ automorphisms. Describe them and explain why they are the only ones.
    d. One of the trees has a vertex of degree $4$. This tree has exactly $3!=6$ automorphisms. Describe them and explain why they are the only ones.
    e. The two remaining trees each have only one vertex of degree $3$ and all other vertices of smaller degree. Each of these trees has exactly two automorphisms. Describe them and explain why they are the only ones.
