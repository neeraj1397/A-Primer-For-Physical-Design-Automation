WORK IN PROGRESS!!!

Here's a guide to understand the repository contents:

Partitioning<br>  
  emsp--> Bipartitioning with Fiduccia-Mattheyses Algorithm<br>  
  emsp emsp    --> Source: [https://web.eecs.umich.edu/~mazum/fmcut1.pdf](https://web.eecs.umich.edu/~mazum/fmcut1.pdf)<br>  
     emsp emsp--> FM_Partition.ipynb: A python notebook containing the function (defined as 'partitionFM()') for bipartitioning with Fiduccia-Mattheyses. The inputs to the function include a dictionary of vertices (representing the nodes in the netlist) and a dictionary of hyper-edges (representing the nets in the netlist).<br>  
     emsp emsp --> FM Partitioning.pdf: A PDF containing the slides explaining the Fiduccia-Mattheyses algorithm steps.<br>  
  emsp--> Bipartitioning with Kernighan-Lin and Integer Linear Programming<br>  
     emsp emsp --> Source: [https://ieeexplore.ieee.org/document/6771089](https://ieeexplore.ieee.org/document/6771089)<br>  
      emsp emsp--> Partition.ipynb: A python notebook containing the function (defined as 'KLPart()') for bipartitioning with Kernighan-Lin algorithm. The notebook also includes the implementation of ILP based approaches to bipartitioning.<br>  
      emsp emsp--> KL Partitioning: A PDF containing the slides explaining the KL Partitioning algorithm steps.<br>  
