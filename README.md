# TuRBO-Penicillin

Project Name: Scalable Bayesian Optimization Accelerates ProcessOptimization of Penicillin Production

## Authors
||                    |
| ------------- | ------------------------------ |
| **AUTHORS**      | Harry Qiaohao Liang     | 
| **VERSION**      | 1.0 / Sep, 2021     | 
| **EMAILS**      | hqliang@mit.edu | 
||                    |

GitHub Repo: https://github.com/HarryQL/TuRBO-Penicillin

Collaborators: Lipeng Lai

Abstract:
While Bayesian Optimization (BO) has emerged as sample-efficient optimization method for accelerating drug discovery, it has rarely been applied to the process optimization of drug manufacturing, which traditionally has relied on human-intuition, along with trial-and-error and slow cycles of learning. The combinatorial and hierarchical complexity of such process control also introduce challenges related to high-dimensional design spaces and requirements of larger scale observations, in which BO has typically scaled poorly. In this paper, we use penicillin manufacturing as a case study to demonstrate the efficacy of BO in accelerating the optimization of typical drug manufacturing processes. To overcome the challenges raised by high dimensionality, we apply a local probabilistic BO approach for global optimization (TuRBO) of penicillin yield and empirically show that it outperforms other BO methods and random baselines. We also extend the study by leveraging BO in the context of multi-objective optimization, allowing us to further evaluate the trade-offs between penicillin yield, production time, and carbon dioxide emission as by-product. Through quantitatively evaluating the performance of BO across high-dimensional optimization and multi-objective optimization on a representative drug manufacturing process, we hope to emphasize the value of BO in this field, popularize application of BO in life sciences, and encourage a closer collaboration between machine learning and broader scientific communities.


## Attribution
This work is under BSD-2-Clause License. Please, acknowledge use of this work with the appropiate citation to the repository and research article.

    
## Usage
run ipython notebook files in each of folders enclosing codes for BO, TuRBO, EBO, and MOBO.







