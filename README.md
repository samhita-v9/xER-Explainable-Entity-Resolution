# xER-Explainable-Entity-Resolution
xER: An Explainable Model for Entity Resolution using an Efficient Solution for the Clique Partitioning Problem

Full paper available at 
https://aclanthology.org/2021.trustnlp-1.5/

Abstract:
In this paper, we propose a global, self- explainable solution to solve a prominent NLP problem: Entity Resolution (ER). We formu- late ER as a graph partitioning problem. Every mention of a real-world entity is represented by a node in the graph, and the pairwise sim- ilarity scores between the mentions are used to associate these nodes to exactly one clique, which represents a real-world entity in the ER domain. In this paper, we use Clique Partition- ing Problem (CPP), which is an Integer Pro- gram (IP) to formulate ER as a graph partition- ing problem and then highlight the explainable nature of this method. Since CPP is NP-Hard, we introduce an efficient solution procedure, the xER algorithm, to solve CPP as a combi- nation of finding maximal cliques in the graph and then performing generalized set packing using a novel formulation. We discuss the advantages of using xER over the traditional methods and provide the computational exper- iments and results of applying this method to ER data sets.
