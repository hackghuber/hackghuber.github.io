---
title: "graph theory thinks"
collection: thinks
type: "maths"
permalink: /thinks/2024-graphtheory
date: 2025-1-1
---

# Graph theory

### degree

degree of a vertex: the number of edges incident to it.`incident` means connected to it.

### complete graph vs connected graph

- complete graph: every pair of vertices is connected by an edge.

- connected graph: there is a path between every pair of vertices.

Note that every complete graph is necessarily connected (one path between any pair of vertices is just to follow the edge between those vertices), but connected graphs are not necessarily complete (for instance, every tree is a connected graph, but $K_{n}
can't be a tree for n ≥ 3, since it must contain a cycle).

`complete` must be `connected`, but `connected` not necessarily `complete`. `complete`>`connected`

### k-connected graph

A graph is k-connected if it has more than k vertices and remains connected whenever fewer than k vertices(k-1) are removed.

### a planar graph

A planar graph is a graph that can be drawn on a plane `without any edges crossing`. That is, the graph can be embedded in a 2D plane such that no two edges intersect except at their endpoints

