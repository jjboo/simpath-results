# simpath-results
Results sharing for the SimPath algorithm with research software created at UBC.

## Research paper

SimPath: An efficient algorithm for influence maximization under the linear threshold model. Amit Goyal, Wei Lu, and Laks V.S. Lakshmanan. In Proc. of the 11th IEEE International Conference on Data Mining (ICDM'11), Vancouver, B.C., December 2011. 

## Software download
Go to http://www.cs.ubc.ca/~welu/downloads.html

## Data
1. youtube-wc: YouTube network (original edge file obtained from http://snap.stanford.edu/data/com-Youtube.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions. 
2. dblp-wc: DBLP network (original edge file obtained from http://snap.stanford.edu/data/com-DBLP.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions.

## IMPORTANT -- Results sharing
Each experiment to be shared in this project should be launched as the only active one on the server as by design, L2 caches are shared with all cores, and it is thus not desirable to run multiple processes for accurate benchmarking purposes.  

If you wish to share your results, create a pull request to include: Your name, email, affliation, CPU and memory information of your machine, results file(s), datasets file(s) (REGARDLESS of whether the data were downloaded from this very repository).