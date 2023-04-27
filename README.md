# 🔍 Finding Connected Components in a Graph:

👨‍💻 This project was completed by Nizar Masmoudi, Ahmed Belgacem, and Fatma Zahra Zakhama.

## 📝 Introduction:
In this project, we addressed the problem of finding connected components in a graph. We defined connected components as disjoint subgraphs in which any two vertices are connected to each other by paths.

* 📚 We used the article "CCF: Fast and Scalable Connected Component Computation in MapReduce" by Hakan Kardes, Siddharth Agrawal, Xin Wang, and Ang Sun as a reference. The article presents a scalable MapReduce approach.

* 💻 Our implementation is based on Spark, and we provided a Spark implementation of the MapReduce algorithm. First, we tested our implementation with a small graph introduced in the article. We used NetworkX for the graph implementation. Then, we applied the algorithm to the Web-Google dataset.

* 🔍 The method proposed in the article for finding connected components in a graph is shown in the figure below:
![image](https://user-images.githubusercontent.com/49822979/234983989-fa1c25fb-bfa6-4adc-90fd-65db372e8c19.png)


* The input of the Connected Component Finder (CCF) module is the edge list. As an output from the module, we want the mapping from each node in the graph to its corresponding componentID. For simplicity, we use the smallest node id in each connected component as the identifier of that component.

* Throughout this notebook we provide a spark implementation to the MapReduce algorithm. First we will try with the small graph introduced in the article to check our implementation is working well. We will use networkx for the graph implementation. Then we will use the Web-Google dataset
