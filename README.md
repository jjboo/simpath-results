# SimPath Results-sharing Project
Results sharing for the SimPath algorithm with research software created at UBC.

## Research papers

- Wei Lu, Xiaokui Xiao, Amit Goyal, Keke Huang, Laks V.S. Lakshmanan. Refutations on "Debunking the Myths of Influence Maximization: An In-Depth Benchmarking Study". Arxiv preprint: https://arxiv.org/abs/1705.05144
- Amit Goyal, Wei Lu, and Laks V.S. Lakshmanan. SimPath: An efficient algorithm for influence maximization under the linear threshold model. In Proc. of the 11th IEEE International Conference on Data Mining (ICDM'11), Vancouver, B.C., December 2011. 

## Software download
For code, sample configs, sample datasets, go to http://www.cs.ubc.ca/~welu/downloads.html

## Data
1. youtube-wc: YouTube network (original edge file obtained from http://snap.stanford.edu/data/com-Youtube.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions. 
2. dblp-wc: DBLP network (original edge file obtained from http://snap.stanford.edu/data/com-DBLP.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions.

## Pull requests information
Pull requests with new results are welcome.  For accurate benchmarking, experiments to be shared should be launched as the only active one on the server.  This is recommended regardless of how many cores the machine has, because by design, caches may be shared with all cores (See e.g., https://en.wikipedia.org/wiki/Smart_Cache), and it is thus not desirable to run multiple processes for accurate benchmarking purposes.  

If you wish to share your results, create a pull request to include: Your name, email, affliation, CPU and memory information of your machine, results file(s), datasets file(s).

If the results are obtained after modifications to the source code at http://www.cs.ubc.ca/~welu/downloads.html, please clearly indicate such in the pull request. 

For Unix-systems, CPU and memory info can be obtained via /proc/cpuinfo and /proc/meminfo.

Unfortunately pull requests with results obtained from a different implementation cannot be included in this repository.

## License and other information
Please do not attempt any modication to files contributed by others, for integrity of results.  As is standard practice with respect to open source projects, by using this repository in any fashion (including but not limited to cloning, contributing, commenting, or using it anywehere else for any purpose), you certify that you have read and you agree with the README file and that you have read and you agree with the LICENSE file.
