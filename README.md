# FastSBL
A fast sparse Bayesian learning algorithm based on gaussian scale mixture model for regression problem

This code is for paper titled "An efficient sparse Bayesian learning algorithm Based on Gaussian-scale mixtures". 

The images in dataset are acquired from http://sparselab.stanford.edu/ and http://decsai.ugr.es/cvg/dbimagenes/.

The function FastLaplace.m in tools corresponds to the fast SBL algorithm based on Laplace priors, which is acquired from the origianl authors at http://www.dbabacan.info/publications.html. The paper is titled "Bayesian Compressive Sensing using Laplace Priors". 

GGAMP-SBL.m corresponds to the algorithm 1 in paper titled "A GAMP based low complexity sparse bayesian learning algorithm".  

For comparison, sparseLab 2.1 and RVM V1.1 toolboxs are needed, which can be obtained from http://sparselab.stanford.edu/ and http://www.miketipping.com/downloads.htm, respectively. 

This code is implemented in Matlab 2019b. If have any questions, please contact zhouwei@hust.edu.cn

If you use any part of our codes, please cite our paper. 

W. Zhou, H. -T. Zhang and J. Wang, "An Efficient Sparse Bayesian Learning Algorithm Based on Gaussian-Scale Mixtures," IEEE Transactions on Neural Networks and Learning Systems, doi: 10.1109/TNNLS.2020.3049056. https://ieeexplore.ieee.org/abstract/document/9334415
 
 bibtex: 

```bibtex
@ARTICLE{zhou2021efficient,
  author={W. {Zhou} and H.-T. {Zhang} and J. {Wang}},
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  title={An Efficient Sparse Bayesian Learning Algorithm Based on Gaussian-Scale Mixtures}, 
  year={2021},
  volume={},
  number={},
  pages={1-14},
  doi={10.1109/TNNLS.2020.3049056}}
```

