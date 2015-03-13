# BNGenerator  Version 0.3 #

![http://sites.poli.usp.br/pmr/ltd/Software/BNGenerator/logoBNGenerator.jpg](http://sites.poli.usp.br/pmr/ltd/Software/BNGenerator/logoBNGenerator.jpg)

_Written by Jaime Ide, created in 2003/01/13, last update in 2010/01/29_

_For instance, visit also the website at Decision Making Lab - University of São Paulo_
http://sites.poli.usp.br/pmr/ltd/Software/BNGenerator/index.html

<a href='http://statcounter.com/p10160831/?guest=1'>View My<br>
Stats</a>


---


## Introduction ##
Bayesian networks are popular representations for uncertainty; the idea is to use a directed acyclic graph and a collection of conditional probability distributions to represent a possibly complex joint probability distribution. Each node in the graph represents a variable, and the edges of the graph represent the direct dependencies among variables.
BNGenerator is a program that generates random Bayesian networks, guaranteeing that the distribution of generated networks is (asymptotically) uniform (we do not generate networks from data!!).The program is coded in Java and is freely distributed under the GNU license.

The program accepts constraints on the maximum degree for nodes and on the maximum number of arcs in the network; these constraints limit how "connected" the networks are. Also, it is possible to control the induced width of the network, leading to more "realistic" networks. Other constraints (for example, maximum number of parents for each node) could be coded with relatively simple modifications in the program; the theoretical analysis of the algorithm and the source code are available, and these modifications should not be too hard.

BNGenerator was coded by Jaime Shinsuke Ide , as a result of research conducted by Jaime S. Ide and Fabio G. Cozman . Ideas and results were based on the work of G. Melançon and M. Bousquet-Melou, and some parts of BNGenerator were directly inspired by the DagAlea software. The research was funded by FAPESP .

<a href='http://www3.clustrmaps.com/user/fedee016'><img src='http://www3.clustrmaps.com/stats/maps-no_clusters/code.google.com-p-bngenerator--thumb.jpg' alt='Locations of visitors to this page' />
</a>