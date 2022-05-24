# <Project Title>
* **Author**: Skip Moses, github: [SkipMoses](https://github.com/SkipMoses)
* **Major**: Mathematics
* **Year**: Senior

# Type of project

Data often has an underlying structure of Geometry that can be modeled a signal on the vertices of a weighted, undirected graph. Historically, graph signal processing (GSP) has focused on modeling smooth signals on a graph, but the increase in availability of abstract data sets has motivated algorithms for learning a valid graph given a set of signals. 

# Purpose 

In this work we attempt to design such a novel methodology for learning a valid graph topology given a set of binary signals on the graph. This is accomplished by extending the ideas of Conditional Logistic Regression and Maximum Likelihood with constraints that enforce a valid graph topology on the regression coefficient matrix. A sufficient understanding of basic linear algebra, graph theory, convex optimization and logistic regression are recommended for reading this work. All code is implemented in python.

# Explanation of files

* `binary_graph_learning` - This file contains the scripts and python notebooks for running the graph learning algorithm
    - Packages: numpy, cvxpy, NetworkX
    - `binary_graph_learning.py`: Contains the functions for learning a graph given a set of noisy signals.
    - `metrics.py`: Computes precision, recall and F-measure given a learned graph adjacency matrix and ground truth adjacency matrix.
    - `erdos_reyni.ipynb`: A python notebook for testing the methodology on an Erdos-Reyni random graph.

*`report.pdf`: This file contains the full write up of the project.

* `poster.html`: This file contains the poster presented at the CSU Chico College of Natural Sciences Poster Session. 
  
# Completion status 

Pending steps include: 

- [X] Synthetic Signal Creation
- [X] Binary Signal Graph Learning
- [X] Graph Visualizations
- [X] Implement matrics for quality analysis.
## Enhancements: 
<List at least 2>

- [ ] Improve hyper parameter optimization.
- [ ] Generalize learning algorithm to Conditional Logistic Regression.

# Can someone else work on this project? 
<Yes>

# Public Display/dissemination

* 2022 CSU Chico College of Natural Sciences Poster Session

# License
