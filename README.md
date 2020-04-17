# Advanced-Graph-MST-Algorithm

<h1>Here we discussed Advanced Graph algorithm</h1>



<h4>Q1.DijKstra Algorithm</h4>
<br>Code : Dijkstra's Algorithm

Given an undirected, connected and weighted graph G(V, E) with V number of vertices (which are numbered from 0 to V-1) and<br> E number of edges.
Find and print the shortest distance from the source vertex (i.e. Vertex 0) to all other vertices (including source vertex also)<br> using Dijkstra's Algorithm.
Print the ith vertex number and the distance from source in one line separated by space. Print different vertices in different<br> lines.<br>
Note : Order of vertices in output doesn't matter.<br>
Input Format :<br>
Line 1: Two Integers V and E (separated by space)<br>
Next E lines : Three integers ei, ej and wi, denoting that there exists an edge between vertex ei and vertex<br> ej <br>with weight wi (separated by space)<br>
Output Format :<br>
In different lines, ith vertex number and its distance from source (separated by space)<br>
Constraints :<br>
2 <= V, E <= 10^5<br>
Sample Input 1 :<br>
4 4<br>
0 1 3<br>
0 3 5<br>
1 2 1<br>
2 3 8<br>
Sample Output 1 :<br>
0 0<br>
1 3<br>
2 4<br>
3 5<br>



<h4>Q2.Prims ALgorithm<h4/>
Code : Prim's Algorithm

Given an undirected, connected and weighted graph G(V, E) with V number of vertices (which are numbered from 0 to V-1)<br> and E number of edges.<br>
Find and print the Minimum Spanning Tree (MST) using Prim's algorithm.<br>
For printing MST follow the steps -<br>
1. In one line, print an edge which is part of MST in the format -<br>
v1 v2 w<br>
where, v1 and v2 are the vertices of the edge which is included in MST and whose weight is w. And v1 <= v2 i.e. print the<br> smaller vertex first while printing an edge.<br>
2. Print V-1 edges in above format in different lines.<br>
Note : Order of different edges doesn't matter.<br>
Input Format :<br>
Line 1: Two Integers V and E (separated by space)<br>
Next E lines : Three integers ei, ej and wi, denoting that there exists an edge between vertex ei and vertex ej with<br> weight wi (separated by space)<br>
Output Format :<br>
MST<br>
Constraints :<br>
2 <= V, E <= 10^5<br>
Sample Input 1 :<br>
4 4<br>
0 1 3<br>
0 3 5<br>
1 2 1<br>
2 3 8<br>
Sample Output 1 :<br>
0 1 3<br>
1 2 1<br>
0 3 5<br>
