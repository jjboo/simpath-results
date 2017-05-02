# simpath-results
Results sharing for the SimPath algorithm with research software created at UBC.

## Research paper

SimPath: An efficient algorithm for influence maximization under the linear threshold model. Amit Goyal, Wei Lu, and Laks V.S. Lakshmanan. In Proc. of the 11th IEEE International Conference on Data Mining (ICDM'11), Vancouver, B.C., December 2011. 

## Software download
For code, configs, data, etc: Go to http://www.cs.ubc.ca/~welu/downloads.html

## Data
1. youtube-wc: YouTube network (original edge file obtained from http://snap.stanford.edu/data/com-Youtube.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions. 
2. dblp-wc: DBLP network (original edge file obtained from http://snap.stanford.edu/data/com-DBLP.html), where the influence weight on directed edge (u,v) = 1 / in-degree of v.  If the graph is undirected, the original edges are directed in both directions.

## IMPORTANT -- Warning
By using this repository in any fashion (including but not limited to cloning, contributing, commenting, or using it anywehere else for any purpose), you agree that you do not have write access to any existing files except for those that are originally contributed by you.  That is, any modication to other's files is __forbidden__.  By using this repository in any fashion (including but not limited to cloning, contributing, commenting, or using it anywehere else for any purpose), you certify that you have read and you agree with this README file and that you have read and you agree with the LICENSE file.

## IMPORTANT -- Definitions of acceptable results / pull requests
Each experiment to be shared in this project should be launched as the __only active one__ on the server.  This should be done __regardless__ of how many cores your machine has. Reason: by design, caches may be shared with all cores of your machine (See e.g., https://en.wikipedia.org/wiki/Smart_Cache), and it is thus not desirable to run multiple processes for accurate benchmarking purposes.  

If you wish to share your results, create a pull request to include: Your name, email, affliation, CPU and memory information of your machine, results file(s), datasets file(s), __REGARDLESS__ of (1) where you obtained the data in the first place, (2) if any modifications to the data was done.  

CPU and memory info should be obtained via /proc/cpuinfo and /proc/meminfo and all original text should be sent.  __No other source of info will be accepted__.

Results obtained from a different implementation will be ignored. Please do not submit those.

Any results 

## When will you respond?
There is __no__ expected timeline for responding to any questions, comments, pull requests, or any other incoming inquiries made in connection with this repository.  In other words, responding is a matter of discretion and any incoming inquiry/request may be ignored.

