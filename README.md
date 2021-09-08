ERDOS - Towards End-to-End Compute Graph Optimization with Graph Neural Networks

Motivation : 

    * The Complexity of Machine Learning Models increases.
    * Computational Demand increases.

But the Models can be optimized to a certain extent only.

Solution :

    Optimization of device placement - Computational Graphs - ML Models
   ![image](https://user-images.githubusercontent.com/64770370/132591377-8eee8299-b2a1-4d7a-990c-e3764e3bbbd4.png)

Goal : 

    To find the best Graph Neural Network (GNN) to perform Node Classification. 

Problem Statement : 

    Existing learning based approaches are sample inefficient -
    * Tackle a single optimization problem.
    * Do not generalize to unseen graphs which makes it infeasible.
    
Prototype Design : 

![image](https://user-images.githubusercontent.com/64770370/132593137-d1c5922a-b8a9-4dfe-be27-b18748cff4ae.png)

Experimental Setup :

Dataset : 

     *  PATTERN
     *  CLUSTER

Devices :

    Nvidia gtx 1650 - Intel i5 CPU - 16GB RAM
    Google Colab - GPU 
              Tesla P100-PCIE-16GB
              Tesla V100-SXM2-16GB 
              Tesla T4, Tesla K80
              
 Models : 
 
    GatedGCN
    MoNet
    GAT

Benchmarking Framework :

    Data pipeline
    GNN layers model
    Training & Evaluation function
    Network and hyperparameter configurations

           




