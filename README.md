# deep-learning-dynamics-paper-list

This is a list of peer-reviewed representative papers on deep learning dynamics (optimization dynamics of neural networks). We hope to enjoy the grand adventure of exploring deep learning dynamics with more researchers. Corrections and suggestions are welcomed. 

# 1. Introduction

The success of deep learning attributes to both deep network architecture and stochastic optimization. Understanding optimization dynamics of neural networks/deep learning dynamics is a key challenge in theoretical foundations of deep learning and a promosing way to further improve empirical success of deep learning. In the context of neural networks, learning dynamical analysis raises new insights and questions beyond conventional convergence analysis of stochastic optimiztion. A large body of related works have been published on top machine learning conferences and journals. However, a lterature review in this line of research is largely missing. It is highly valuable to continuously collect and share these great works. This is exactly the main purpose of the paper list. 

The paper list mainly includes four important directions in the context of deep learning:

(1) Learning Dynamics of SGD,

(2) Learning Dynmaics of Adaptive Gradient Methods,

(3) Learning Dynamics with Training Techniques (e.g. Weight Decay, Normalization Layers, Gradient Clipping, Noise Injection, etc.),

(4) Learning Dynamics beyond Standard Training (e.g. SGLD, Vicinal Risk Minimization, Private Training, etc.).


# 2. Learning Dynamics of SGD

- Stochastic gradient descent as approximate bayesian inference. In *JMRL 2017*. [[pdf](https://www.jmlr.org/papers/volume18/17-214/17-214.pdf?ref=https://githubhelp.com)]
- How to escape saddle points efficiently. In *ICML 2017*. [[pdf](http://proceedings.mlr.press/v70/jin17a/jin17a.pdf)]
- A bayesian perspective on generalization and stochastic gradient descent. In *ICLR 2018*. [[pdf](https://openreview.net/pdf?id=BJij4yg0Z)]
- Stochastic gradient descent performs variational inference, converges to limit cycles for deep networks. In *ITA 2018*. [[pdf](https://arxiv.org/pdf/1710.11029.pdf)]
- An alternative view: When does SGD escape local minima? In *ICML 2018*. [[pdf](http://proceedings.mlr.press/v80/kleinberg18a/kleinberg18a.pdf)]
- Escaping saddles with stochastic gradients. In *ICML 2018*. [[pdf](http://proceedings.mlr.press/v80/daneshmand18a/daneshmand18a.pdf)]
- How sgd selects the global minima in over-parameterized learning: A dynamical stability perspective. In *NeurIPS 2018*. [[pdf](https://proceedings.neurips.cc/paper/2018/file/6651526b6fb8f29a00507de6a49ce30f-Paper.pdf)]
- Stochastic modified equations and dynamics of stochastic gradient algorithms i: Mathematical foundations. In *JMLR 2019*. [[pdf](https://www.jmlr.org/papers/volume20/17-526/17-526.pdf)]
- On the diffusion approximation of nonconvex stochastic gradient descent. In *AMSA 2019*. [[pdf](https://par.nsf.gov/servlets/purl/10199185)]
- The anisotropic noise in stochastic gradient descent: Its behavior of escaping from sharp minima and regularization effects. In *ICML 2019*. [[pdf](https://arxiv.org/pdf/1803.00195.pdf)]
- Which algorithmic choices matter at which batch sizes? insights from a noisy quadratic model. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/e0eacd983971634327ae1819ea8b6214-Paper.pdf)]
- First exit time analysis of stochastic gradient descent under heavy-tailed gradient noise. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/a97da629b098b75c294dffdc3e463904-Paper.pdf)]
- A diffusion theory for deep learning dynamics: Stochastic gradient descent exponentially favors flat minima. In *ICLR 2021*. [[pdf](https://openreview.net/pdf?id=wXgk_iCiYGo)]
- On the validity of modeling sgd with stochastic differential equations (sdes). In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/69f62956429865909921fa916d61c1f8-Paper.pdf)]
- Shape matters: Understanding the implicit bias of the noise covariance. In *COLT 2021*. [[pdf](http://proceedings.mlr.press/v134/haochen21a/haochen21a.pdf)]
- Three-stage evolution and fast equilibrium for SGD with non-degenerate critical points. In *ICML 2022*. [[pdf](http://www.personal.psu.edu/zxw14/research/ThreeStageEquilibrium.pdf)]

# 3. Learning Dynmaics of Adaptive Gradient Methods

- Stochastic modified equations and adaptive stochastic gradient algorithms. In *ICML 2017*. [[pdf](http://proceedings.mlr.press/v70/li17f/li17f.pdf)]
- Escaping saddle points with adaptive gradient methods. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/staib19a/staib19a.pdf)]
- Towards theoretically understanding why sgd generalizes better than adam in deep learning. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/f3f27a324736617f20abbf2ffd806f6d-Paper.pdf)]
- Adaptive inertia: Disentangling the effects of adaptive learning rate and momentum. In *ICML 2022*. [[pdf](https://arxiv.org/pdf/2006.15815.pdf)]

# 4. Learning Dynamics with Training Techniques

- Toward understanding the importance of noise in training neural networks. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/zhou19d/zhou19d.pdf)]
- Why gradient clipping accelerates training: A theoretical justification for adaptivity. In *ICLR 2020*. [[pdf](https://arxiv.org/pdf/1905.11881.pdf)]

# 5. Learning Dynamics beyond Standard Training

## 5.1 SGLD

- Bayesian learning via stochastic gradient langevin dynamics. In *ICML 2011*. [[pdf](https://icml.cc/2011/papers/398_icmlpaper.pdf)]
- Approximation analysis of stochastic gradient langevin dynamics by using fokker-planck equation and ito process. In *ICML 2014*. [[pdf](http://proceedings.mlr.press/v32/satoa14.pdf)]
- A hitting time analysis of stochastic gradient langevin dynamics. In *COLT 2017*. [[pdf]([http://proceedings.mlr.press/v65/raginsky17a/raginsky17a.pdf](http://proceedings.mlr.press/v65/zhang17b/zhang17b.pdf)]
- Non-convex learning via stochastic gradient langevin dynamics: a nonasymptotic analysis. In *COLT 2017*. [[pdf](http://proceedings.mlr.press/v65/raginsky17a/raginsky17a.pdf)]
- Global convergence of langevin dynamics based algorithms for nonconvex optimization. In *NeurIPS 2018*. [[pdf](https://proceedings.neurips.cc/paper/2018/file/9c19a2aa1d84e04b0bd4bc888792bd1e-Paper.pdf)]







