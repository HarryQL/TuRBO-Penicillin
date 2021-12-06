# TuRBO-Penicillin

Project Name: Scalable Bayesian Optimization Accelerates ProcessOptimization of Penicillin Production

## Authors
||                    |
| ------------- | ------------------------------ |
| **AUTHORS**      | Qiaohao Liang     | 
| **VERSION**      | 1.0 / Sep, 2021     | 
| **EMAILS**      | hqliang@mit.edu | 
||                    |

GitHub Repo: https://github.com/HarryQL/TuRBO-Penicillin

Collaborators: Lipeng Lai

Abstract:
While Bayesian Optimization (BO) has emerged as sample-efficient optimization method for accelerating drug discovery, it has rarely been applied to the process optimization of pharmaceutical manufacturing, which traditionally has relied on human-intuition, along with trial-and-error and slow cycles of learning. The combinatorial and hierarchical complexity of such process control also introduce challenges related to high-dimensional design spaces and requirements of larger scale observations, in which BO has typically scaled poorly. In this paper, we use penicillin production as a case study to demonstrate the efficacy of BO in accelerating the optimization of typical pharmaceutical manufacturing processes. To overcome the challenges raised by high dimensionality, we apply a trust region BO approach (TuRBO) for global optimization of penicillin yield and empirically show that it outperforms other BO and random baselines. We also extend the study by leveraging BO in the context of multi-objective optimization, allowing us to further evaluate the trade-offs between penicillin yield, production time, and carbon dioxide emission as by-product. Through quantifying the performance of BO across high-dimensional and multi-objective drug production optimization processes, we hope to popularize application of BO in this field, and encourage closer collaboration between machine learning and broader scientific communities.


## Attribution
This work is under BSD-2-Clause License. Please, acknowledge use of this work with the appropiate citation to the repository and research article.

    
## Usage
Run ipython notebook files in each of folders enclosing codes for BO, TuRBO, EBO, and MOBO.

## Citations and References

To cite our work, please use 

    @inproceedings{
    liang2021scalable,
    title={Scalable Bayesian Optimization Accelerates Process Optimization of Penicillin Production},
    author={Qiaohao Liang and Lipeng Lai},
    booktitle={NeurIPS 2021 AI for Science Workshop},
    year={2021},
    url={https://openreview.net/forum?id=UVdSYXMNdOe}
    }
        
