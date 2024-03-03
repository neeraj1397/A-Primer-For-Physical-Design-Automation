WORK IN PROGRESS!!!

Here's a guide to understand the repository contents:

Partitioning
  --> Bipartitioning with Fiduccia-Mattheyses Algorithm
      --> Source: [](https://web.eecs.umich.edu/~mazum/fmcut1.pdf)
      --> FM_Partition.ipynb: A python notebook containing the function (defined as 'partitionFM()') for bipartitioning with Fiduccia-Mattheyses. The inputs to the function include a dictionary of vertices (representing the nodes in the netlist) and a dictionary of hyper-edges (representing the nets in the netlist).
      --> FM Partitioning.pdf: A PDF containing the slides explaining the Fiduccia-Mattheyses algorithm steps.
  --> Bipartitioning with Kernighan-Lin and Integer Linear Programming
      --> Source: [](https://ieeexplore.ieee.org/document/6771089)
      --> Partition.ipynb: A python notebook containing the function (defined as 'KLPart()') for bipartitioning with Kernighan-Lin algorithm. The notebook also includes the implementation of ILP based approaches to bipartitioning.
      --> KL Partitioning: A PDF containing the slides explaining the KL Partitioning algorithm steps.
