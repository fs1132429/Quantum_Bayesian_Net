# Quantum_Bayesian_Net

In this project, we identify two Bayesian networks in finance that possess significant inference capabilities. Recognizing that Bayesian inference is NP-hard, our goal is to transform this problem to achieve quantum inference, for which a quadratic speedup has been theoretically demonstrated (Low et al., 2014). 

We first selected two finance-related problems and preprocessed the data to develop corresponding Bayesian networks. We also employed a structural learning algorithm for this purpose. Following that, we performed classical inference on these two Bayesian networks, which contained 4 and 8 nodes, respectively. To understand quantum inference, we meticulously reconstructed the methodologies outlined in papers (Borujeni et al., 2020) and (Low et al., 2014), gaining a comprehensive understanding of their approaches and developing code that was not provided in the original publications. This involved a detailed examination of how each Bayesian network is converted into its corresponding quantum circuit and how inference is obtained by simulating the quantum circuit. 

Although the Bayesian networks analyzed in this study can be easily solved using classical inference methods, our work lays the groundwork for applying quantum inference techniques to larger networks, where classical methods may become infeasible. 

Low, G. H., Yoder, T. J., & Chuang, I. L. (2014). Quantum inference on Bayesian networks. Physical Review A, 89(6). https://doi.org/10.1103/physreva.89.062315

Borujeni, S. E., Nannapaneni, S., Nguyen, N. H., Behrman, E. C., & Steck, J. E. (2020, April 29). Quantum circuit representation of Bayesian networks. arXiv.org. https://arxiv.org/abs/2004.14803
