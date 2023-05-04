Download Link: https://assignmentchef.com/product/solved-cs70-homework3
<br>
Before you start your homework, state briefly how you worked on it. Who else did you work with?

List names and email addresses. (In case of homework party, you can just describe the group.)

<h1>1          Short Answer: Graphs</h1>

<ul>

 <li>Bob removed a degree 3 node in an <em>n</em>-vertex tree, how many connected components are in the resulting graph? (An expression that may contain <em>n</em>.)</li>

 <li>Given an <em>n</em>-vertex tree, Bob added 10 edges to it, then Alice removed 5 edges and the resulting graph has 3 connected components. How many edges must be removed to remove all cycles in the resulting graph? (An expression that may contain <em>n</em>.)</li>

 <li>True or False: For all <em>n </em>3, the complete graph on <em>n </em>vertices, <em>K<sub>n </sub></em>has more edges than the <em>n</em>-dimensional hypercube. Justify your answer.</li>

 <li>A complete graph with <em>n </em>vertices where <em>n </em>is an odd prime can have all its edges covered with <em>x </em>Hamiltonian cycles (a Hamiltonian cycle is a cycle where each vertex appears exactly once). What is the number, <em>x</em>, of such cycles required to cover the a complete graph? (Answer should be an expression that depends on <em>n</em>.)</li>

 <li>Give a set of edge-disjoint Hamiltonian cycles that covers the edges of <em>K</em><sub>5</sub>, the complete graph on 5 vertices. (Each path should be a sequence (or list) of edges in <em>K</em><sub>5</sub>, where an edge is written as a pair of vertices from the set {0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>4} – e.g: (0<em>,</em>1)<em>,</em>(1<em>,</em>2).)</li>

</ul>

<h1>2          Eulerian Tour and Eulerian Walk</h1>

<ul>

 <li>Is there an Eulerian tour in the graph above?</li>

 <li>Is there an Eulerian walk in the graph above?</li>

 <li>What is the condition that there is an Eulerian walk in an undirected graph? Briefly justfy your answer.</li>

</ul>

<h1>3          Bipartite Graph</h1>

A bipartite graph consists of 2 disjoint sets of vertices (say <em>L </em>and <em>R</em>), such that no 2 vertices in the same set have an edge between them. For example, here is a bipartite graph (with <em>L </em>= {green vertices} and <em>R </em>={red vertices}), and a non-bipartite graph.

Figure 1: A bipartite graph (left) and a non-bipartite graph (right).

Prove that a graph is bipartite if and only if it has no tours of odd length.

<h1>4          Hypercubes</h1>

The vertex set of the{and only if <em>n</em>-dimensional hypercube <em>G </em>= (<em>V</em><em>,E</em>) is given by <em>V </em>= {0<em>,</em>1}<em><sup>n </sup></em>(<em>x</em>recall thatand <em>y </em>if

0<em>,</em>1}<em><sup>n </sup></em>denotes the set of all<em>x </em>and <em>y </em>differ in exactly one bit position. These problems will help you understand<em>n</em>-bit strings). There is an edge between two vertices hypercubes.

<ul>

 <li>Draw 1-, 2-, and 3-dimensional hypercubes and label the vertices using the corresponding bit strings.</li>

 <li>Show that for any <em>n </em>1, the <em>n</em>-dimensional hypercube is <em>bipartite</em>: the vertices can be partitioned into two groups so that every edge goes between the two groups.</li>

</ul>

<h1>5          Triangulated Planar Graph</h1>

In this problem you will prove that every triangulated planar graph (every face has 3 sides; that is, every face has three edges bordering it, including the unbounded face) contains either (1) a vertex of degree 1, 2, 3, 4, (2) two degree 5 vertices which are adjacent, or (3) a degree 5 and a degree 6 vertices which are adjacent. Justify your answers.

(a) Place a “charge” on each vertex <em>v </em>of value 6 degree(<em>v</em>). What is the sum of the charges on all the vertices? (<em>Hint</em>: Use Euler’s formula and the fact that the planar graph is triangulated.) (b) What is the charge of a degree 5 vertex and of a degree 6 vertex?

<ul>

 <li>Suppose now that we shift 1<em>/</em>5 of the charge of a degree 5 vertex to each of its neighbors that has a negative charge. (We refer to this as “discharging” the degree 5 vertex.) Conclude the proof under the assumption that, after discharging all degree 5 vertices, there is a degree 5 vertex with positive remaining charge.</li>

 <li>If no degree 5 vertices have positive charge after discharging the degree 5 vertices, does there exist any vertex with positive charge after discharging? If there is such a vertex, what are the possible degrees of that vertex?</li>

 <li>Suppose there exists a degree 7 vertex with positive charge after discharging the degree 5 vertices. How many neighbors of degree 5 might it have?</li>

 <li>Continuing from Part (e). Since the graph is triangulated, are two of these degree 5 vertices adjacent?</li>

 <li>Finish the proof from the facts you obtained from the previous parts.</li>

</ul>