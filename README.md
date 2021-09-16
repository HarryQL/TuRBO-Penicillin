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
Run ipython notebook files in each of folders enclosing codes for BO, TuRBO, EBO, and MOBO.

## Citations and References
The original version of applied TuRBO algorithm can be found at 

    @inproceedings{eriksson2019scalable,
      title = {Scalable Global Optimization via Local {Bayesian} Optimization},
      author = {Eriksson, David and Pearce, Michael and Gardner, Jacob and Turner, Ryan D and Poloczek, Matthias},
      booktitle = {Advances in Neural Information Processing Systems},
      pages = {5496--5507},
      year = {2019},
      url = {http://papers.nips.cc/paper/8788-scalable-global-optimization-via-local-bayesian-optimization.pdf},
    }
    
The original version of applied EBO algorithm can be found at 

    @inproceedings{wang2018batched,
      title={Batched large-scale Bayesian optimization in high-dimensional spaces},
      author={Wang, Zi and Gehring, Clement and Kohli, Pushmeet and Jegelka, Stefanie},
      booktitle={International Conference on Artificial Intelligence and Statistics},
      pages={745--754},
      year={2018},
      organization={PMLR}
    }
    
The original version of applied EHVI acquisition function in MOBO can be found at 

    @article{yang2019efficient,
      title={Efficient computation of expected hypervolume improvement using box decomposition algorithms},
      author={Yang, Kaifeng and Emmerich, Michael and Deutz, Andr{\'e} and B{\"a}ck, Thomas},
      journal={Journal of Global Optimization},
      volume={75},
      number={1},
      pages={3--34},
      year={2019},
      publisher={Springer}
    }







