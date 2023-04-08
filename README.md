# Node-embedding-Based-Influence-Maximization-Algorithm-in-Temporal-Networks

## About
This project provide datasets that are used in the paper "基于时序网络节点嵌入的影响力最大化算法 (A node-embedding based influence maximization
algorithm in temporal network)".

## Data Description
All datasets are stored in a form of $(u_i, u_j, t)$, where $u_i$, $u_j$ represent node $i$ and node $j$, respectively, and $t$ records the established time of a temporal edge. The edges are turned into undirected ones in this paper. 
- `EEU1 & EEU2` : These two datasets collect email data from an European research institution. An edge $(u_i, u_j, t)$ means user $u_i$ sent an email to user $u_j$ at time $t$.
- `haggle` : This dataset records contact between people. An edge $(u_i, u_j, t)$ means a person $u_i$ has a contact with another person $u_j$ at time $t$.
- `hs2013` : This dataset collects the contact data between persons in a high school. An edge $(u_i, u_j, t)$ means a person $u_i$ has a contact with another person $u_j$ at time $t$.
- `ht2009` : This dataset was collected during the ACM Hypertext 2009 conference. If a person  $u_i$ contact with another $u_j$ at time $t$, an edge is recorded.
- `PS` : This dataset collects the contacts between the children and teachers in a primary school. An edge $(u_i, u_j, t)$ means a person $u_i$ has a contact with another person $u_j$ at time $t$.
