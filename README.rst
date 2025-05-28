============
python-graph
============


A library for working with graphs in Python
-------------------------------------------

This software provides a suitable data structure for representing graphs and a
whole set of important algorithms.


INSTALLING
----------

To install the core module, run:

	pip install python-graph

To install the dot language support, run:

	pip install python-graph[dot]


DOCUMENTATION
-------------

FIXME: Module documentation isn't available


WEBSITE
-------

The latest version of this package can be found at:

	https://github.com/Shoobx/python-graph

Please report bugs at:

	https://github.com/Shoobx/python-graph/issues


PROJECT COMMITTERS
------------------

Pedro Matiello <pmatiello@gmail.com>
	* Original author;
	* Graph, Digraph and Hipergraph classes;
	* Accessibility algorithms;
	* Cut-node and cut-edge detection;
	* Cycle detection;
	* Depth-first and Breadth-first searching;
	* Minimal Spanning Tree (Prim's algorithm);
	* Random graph generation;
	* Topological sorting;
	* Traversals;
	* XML reading/writing;
	* Refactoring.

Christian Muise <christian.muise@gmail.com>
	* Dot file reading/writing;
	* Hypergraph class;
	* Refactoring.

Salim Fadhley <sal@stodge.org>
	* Porting of Roy Smith's A* implementation to python-graph;
	* Edmond Chow's heuristic for A*;
	* Refactoring.

Tomaz Kovacic <tomaz.kovacic@gmail.com>
	* Transitive edge detection;
	* Critical path algorithm;
	* Bellman-Ford algorithm;
	* Logo design.


CONTRIBUTORS
------------

Eugen Zagorodniy <e.zagorodniy@gmail.com>
	* Mutual Accessibility (Tarjan's Algorithm).

Johannes Reinhardt <jreinhardt@ist-dein-freund.de>
	* Maximum-flow algorithm;
	* Gomory-Hu cut-tree algorithm;
	* Refactoring.

Juarez Bochi <jbochi@gmail.com>
	* Pagerank algorithm.

Nathan Davis <davisn90210@gmail.com>
	* Faster node insertion.

Paul Harrison <pfh@logarithmic.net>
	* Mutual Accessibility (Tarjan's Algorithm).

Peter Sagerson <peter.sagerson@gmail.com>
	* Performance improvements on shortest path algorithm.

Rhys Ulerich <rhys.ulerich@gmail.com>
	* Dijkstra's Shortest path algorithm.

Roy Smith <roy@panix.com>
	* Heuristic Searching (A* algorithm).

Zsolt Haraszti <zsolt@drawwell.net>
	* Weighted random generated graphs.

Anand Jeyahar  <anand.jeyahar@gmail.com>
	* Edge deletion on hypergraphs (bug fix).

Emanuele Zattin <emanuelez@gmail.com>
	* Hyperedge relinking (bug fix).

Jonathan Sternberg <jonathansternberg@gmail.com>
	* Graph comparison (bug fix);
	* Proper isolation of attribute lists (bug fix).

Daniel Merritt <dmerritt@gmail.com>
	* Fixed reading of XML-stored graphs with edge attributes.

Sandro Tosi <morph@debian.org>
	* Some improvements to Makefile

Robin Harms Oredsson <robin@betahaus.net>
	* Repackaging and modernization to make it work with python3 and modern distribution.
	* Typing

LICENSE
-------

This software is provided under the MIT license. See accompanying COPYING file
for details.
