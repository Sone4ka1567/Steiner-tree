# Steiner-tree

## Introduction
Given an undirected connected graph G = (V, E), a vertex r is highlighted, and a set of vertices $V_0$. There are also weights on the edges ω: E → R+. For a tree T, covering r and all vertices  $V_0$, costs are defined as follows:
(a) If edge e passes through k < M shortest paths from vertices $V_0$ to the root r, then the edge contributes kwe (each of the vertices "rents" the edge).
(b) If edge e passes through k >= M shortest paths from vertices $V_0$ to the root r, then the edge contributes Mwe (vertices collectively "buy" the edge).
The goal is to find the tree T of minimal weight, covering all vertices $V_0$ and r.

## Explanation
The problem is a modification of the usual Steiner tree problem with the imposition of an additional condition
- the weights of the edges will be multiplied by a certain number depending on this condition.

## What is needed to show in the project

1) Prove that checking for the existence of a tree with a weight no more than k is NP-complete.

2) Reduce the problem to the metric version (in the metric version, the initial graph is complete and w(x, z) ⩽ w(x, y) + w(y, z) is true.

3) Based on the algorithm for finding the Steiner tree, construct an algorithm that provides a 2-approximation for the metric version of the problem and implement it.

