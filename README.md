# deep-learning-dynamics-paper-list

This is a list of peer-reviewed representative papers on deep learning dynamics (optimization dynamics of neural networks). We hope to enjoy the grand adventure of exploring deep learning dynamics with more researchers. Corrections and suggestions are welcomed. 

# 1. Introduction

The success of deep learning attributes to both deep network architecture and stochastic optimization. Understanding optimization dynamics of neural networks/deep learning dynamics is a key challenge in theoretical foundations of deep learning and a promising way to further improve empirical success of deep learning. We consider learning dynamics of optimization as a reductionism approach. Many deep learning techniques can be analyzed and interpreted from a dynamical perspective. In the context of neural networks, learning dynamical analysis provides new insights and theories beyond conventional convergence analysis of stochastic optimiztion. A large body of related works have been published on top machine learning conferences and journals. However, a lterature review in this line of research is largely missing. It is highly valuable to continuously collect and share these great works. This is exactly the main purpose of the paper list. Note that this paper list does not focus on the conventional convergence analysis in optimization and forward dynamics of neural networks.

The paper list mainly covers four important directions:

(1) Learning Dynamics of GD and SGD,

(2) Learning Dynmaics of Adaptive Gradient Methods,

(3) Learning Dynamics with Training Techniques (e.g. Weight Decay, Normalization Layers, Gradient Clipping, etc.),

(4) Learning Dynamics beyond Standard Training (e.g. Self-Supervised Learning, Continual Learning, Privacy, etc.).


# 2. Learning Dynamics of GD and SGD

- Gradient descent only converges to minimizers. In *COLT 2016*. [[pdf](http://proceedings.mlr.press/v49/lee16.pdf)]
- Stochastic gradient descent as approximate bayesian inference. In *JMLR 2017*. [[pdf](https://www.jmlr.org/papers/volume18/17-214/17-214.pdf?ref=https://githubhelp.com)]
- How to escape saddle points efficiently. In *ICML 2017*. [[pdf](http://proceedings.mlr.press/v70/jin17a/jin17a.pdf)]
- Gradient descent can take exponential time to escape saddle points. In *NeurIPS 2017*/ [[pdf](https://proceedings.neurips.cc/paper/2017/file/f79921bbae40a577928b76d2fc3edc2a-Paper.pdf)]
- A bayesian perspective on generalization and stochastic gradient descent. In *ICLR 2018*. [[pdf](https://openreview.net/pdf?id=BJij4yg0Z)]
- Stochastic gradient descent performs variational inference, converges to limit cycles for deep networks. In *ITA 2018*. [[pdf](https://arxiv.org/pdf/1710.11029.pdf)]
- An alternative view: When does SGD escape local minima? In *ICML 2018*. [[pdf](http://proceedings.mlr.press/v80/kleinberg18a/kleinberg18a.pdf)]
- On the optimization of deep networks: Implicit acceleration by overparameterization. In *ICML 2018*. [[pdf](http://proceedings.mlr.press/v80/arora18a/arora18a.pdf)]
- How sgd selects the global minima in over-parameterized learning: A dynamical stability perspective. In *NeurIPS 2018*. [[pdf](https://proceedings.neurips.cc/paper/2018/file/6651526b6fb8f29a00507de6a49ce30f-Paper.pdf)]
- Neural tangent kernel: Convergence and generalization in neural networks. In *NeurIPS 2018*. [[pdf](https://proceedings.neurips.cc/paper/2018/file/5a4be1fa34e62bb8a6ec6b91d2462f5a-Paper.pdf)]
- Stochastic modified equations and dynamics of stochastic gradient algorithms i: Mathematical foundations. In *JMLR 2019*. [[pdf](https://www.jmlr.org/papers/volume20/17-526/17-526.pdf)]
- On the diffusion approximation of nonconvex stochastic gradient descent. In *AMSA 2019*. [[pdf](https://par.nsf.gov/servlets/purl/10199185)]
- Gradient descent provably optimizes over-parameterized neural networks. In *ICLR 2019*. [[pdf](http://proceedings.mlr.press/v97/du19c/du19c.pdf)]
- The anisotropic noise in stochastic gradient descent: Its behavior of escaping from sharp minima and regularization effects. In *ICML 2019*. [[pdf](https://arxiv.org/pdf/1803.00195.pdf)]
- Gradient descent finds global minima of deep neural network. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/du19c/du19c.pdf)]
- Which algorithmic choices matter at which batch sizes? insights from a noisy quadratic model. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/e0eacd983971634327ae1819ea8b6214-Paper.pdf)]
- First exit time analysis of stochastic gradient descent under heavy-tailed gradient noise. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/a97da629b098b75c294dffdc3e463904-Paper.pdf)]
- Wide neural networks of any depth evolve as linear models under gradient descent. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/0d1a9651497a38d8b1c3871c84528bd4-Paper.pdf)]
- On the noisy gradient descent that generalizes as sgd. In *ICML 2020*. [[pdf](http://proceedings.mlr.press/v119/wu20c/wu20c.pdf)]
- Stochastic gradient and Langevin processes. In *ICML 2020*. [[pdf](http://proceedings.mlr.press/v119/cheng20e/cheng20e.pdf)]
- An empirical study of stochastic gradient descent with structured covariance noise. In *AISTATS 2020*. [[pdf](http://proceedings.mlr.press/v108/wen20a/wen20a.pdf)]
- Stochasticity of deterministic gradient descent: Large learning rate for multiscale objective function. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/1b9a80606d74d3da6db2f1274557e644-Paper.pdf)]
- The surprising simplicity of the early-time learning dynamics of neural networks. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/c6dfc6b7c601ac2978357b7a81e2d7ae-Paper.pdf)]
- Dynamical mean-field theory for stochastic gradient descent in Gaussian mixture classification. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/6c81c83c4bd0b58850495f603ab45a93-Paper.pdf)]
- A diffusion theory for deep learning dynamics: Stochastic gradient descent exponentially favors flat minima. In *ICLR 2021*. [[pdf](https://openreview.net/pdf?id=wXgk_iCiYGo)]
- On the origin of implicit regularization in stochastic gradient descent. In *ICLR 2021*. [[pdf](https://arxiv.org/pdf/2101.12176.pdf)]
- Noise and fluctuation of finite learning rate stochastic gradient descent. In *ICML 2021*. [[pdf](http://proceedings.mlr.press/v139/liu21ad/liu21ad.pdf)]
- The heavy-tail phenomenon in SGD. In *ICML 2021*. [[pdf](http://proceedings.mlr.press/v139/gurbuzbalaban21a/gurbuzbalaban21a.pdf)]
- Positive-negative momentum: Manipulating stochastic gradient noise to improve generalization. In *ICML 2021*. [[pdf](http://proceedings.mlr.press/v139/xie21h/xie21h.pdf)]
- Sgd: The role of implicit regularization, batch-size and multiple-epochs. In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/e64c9ec33f19c7de745bd6b6d1a7a86e-Paper.pdf)]
- On the validity of modeling sgd with stochastic differential equations (sdes). In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/69f62956429865909921fa916d61c1f8-Paper.pdf)]
- Label noise sgd provably prefers flat global minimizers. In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/e6af401c28c1790eaef7d55c92ab6ab6-Paper.pdf)]
- Imitating deep learning dynamics via locally elastic stochastic differential equations. In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/327af0f71f7acdfd882774225f04775f-Paper.pdf)]
- Shape matters: Understanding the implicit bias of the noise covariance. In *COLT 2021*. [[pdf](http://proceedings.mlr.press/v134/haochen21a/haochen21a.pdf)]
- Sgd with a constant large learning rate can converge to local maxima. In *ICLR 2022*. [[pdf](https://openreview.net/pdf?id=9XhPLAjjRB)]
- Strength of minibatch noise in sgd. In *ICLR 2022*. [[pdf](https://arxiv.org/pdf/2102.05375.pdf)]
- What Happens after SGD Reaches Zero Loss?--A Mathematical Framework. In *ICLR 2022*. [[pdf](https://openreview.net/pdf?id=siCt4xZn5Ve)]
- Eliminating Sharp Minima from SGD with Truncated Heavy-tailed Noise. In *ICLR 2022*. [[pdf](https://openreview.net/pdf?id=B3Nde6lvab)]
- Large Learning Rate Tames Homogeneity: Convergence and Balancing Effect. In *ICLR 2022*. [[pdf](https://openreview.net/pdf?id=3tbDrs77LJ5)]
- Neural Network Weights Do Not Converge to Stationary Points: An Invariant Measure Perspective. In *ICML 2022*. [[pdf](https://proceedings.mlr.press/v162/zhang22q/zhang22q.pdf)]
- Three-stage evolution and fast equilibrium for sgd with non-degenerate critical points. In *ICML 2022*. [[pdf](http://www.personal.psu.edu/zxw14/research/ThreeStageEquilibrium.pdf)]
- Power-law escape rate of sgd. In *ICML 2022*. [[pdf](https://arxiv.org/pdf/2105.09557.pdf)]


# 3. Learning Dynmaics of Adaptive Gradient Methods

- Stochastic modified equations and adaptive stochastic gradient algorithms. In *ICML 2017*. [[pdf](http://proceedings.mlr.press/v70/li17f/li17f.pdf)]
- Escaping saddle points with adaptive gradient methods. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/staib19a/staib19a.pdf)]
- Towards theoretically understanding why sgd generalizes better than adam in deep learning. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/f3f27a324736617f20abbf2ffd806f6d-Paper.pdf)]
- Adaptive inertia: Disentangling the effects of adaptive learning rate and momentum. In *ICML 2022*. [[pdf](https://arxiv.org/pdf/2006.15815.pdf)]


# 4. Learning Dynamics with Training Techniques

- L2 regularization versus batch and weight normalization. In *NeurIPS 2017*. [[pdf](https://arxiv.org/pdf/1706.05350.pdf)]
- Three mechanisms of weight decay regularization. In *ICLR 2018*. [[pdf](https://arxiv.org/pdf/1810.12281.pdf)]
- Norm matters: efficient and accurate normalization schemes in deep networks. In *NeurIPS 2018*. [[pdf](https://proceedings.neurips.cc/paper/2018/file/a0160709701140704575d499c997b6ca-Paper.pdf)]
- Theoretical analysis of auto rate-tuning by batch normalization. In *ICLR 2019*. [[pdf](https://arxiv.org/pdf/1812.03981.pdf)]
- Toward understanding the importance of noise in training neural networks. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/zhou19d/zhou19d.pdf)]
- A quantitative analysis of the effect of batch normalization on gradient descent. In *ICML 2019*. [[pdf](https://proceedings.mlr.press/v97/cai19a/cai19a.pdf)]
- Why gradient clipping accelerates training: A theoretical justification for adaptivity. In *ICLR 2020*. [[pdf](https://arxiv.org/pdf/1905.11881.pdf)]
- On the training dynamics of deep networks with L2 regularization. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/32fcc8cfe1fa4c77b5c58dafd36d1a98-Paper.pdf)]
- Reconciling modern deep learning with traditional optimization analyses: The intrinsic learning rat. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/a7453a5f026fb6831d68bdc9cb0edcae-Paper.pdf)]
- Spherical Motion Dynamics: Learning Dynamics of Normalized Neural Network using SGD and Weight Decay. In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/326a8c055c0d04f5b06544665d8bb3ea-Paper.pdf)]


# 5. Learning Dynamics beyond Standard Training

- Variational annealing of gans: A langevin perspective. In *ICML 2019*. [[pdf](http://proceedings.mlr.press/v97/tao19a/tao19a.pdf)]
- Dynamics of stochastic gradient descent for two-layer neural networks in the teacher-student setup. In *NeurIPS 2019*. [[pdf](https://proceedings.neurips.cc/paper/2019/file/cab070d53bd0d200746fb852a922064a-Paper.pdf)]
- On the dynamics of gradient descent for autoencoders. In *AISTAT 2019*. [[pdf](http://proceedings.mlr.press/v89/nguyen19a/nguyen19a.pdf)]
- Understanding the role of training regimes in continual learning. In *NeurIPS 2020*. [[pdf](https://proceedings.neurips.cc/paper/2020/file/518a38cc9a0173d0b2dc088166981cf8-Paper.pdf)]
- Layer-wise conditioning analysis in exploring the learning dynamics of dnns. In *ECCV 2020*. [[pdf](https://arxiv.org/pdf/2002.10801.pdf)]
- Understanding self-supervised learning dynamics without contrastive pairs. In *ICML 2021*. [[pdf](http://proceedings.mlr.press/v139/tian21a/tian21a.pdf)]
- Differential privacy dynamics of langevin diffusion and noisy gradient descent. In *NeurIPS 2021*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/7c6c1a7bfde175bed616b39247ccace1-Paper.pdf)]

# Citing

If you find the paper list useful for your research, you are highly welcomed to cite our representative work on this topic. We hope that our extended journal paper based on ICML 2022 "Adaptive Inertia", which formally reviews the paper list of deep learning dynamics, will appear in near future.

[1] **ICML 2022 (Oral)**: SGD and Adam dynamics for saddle-point escaping and minima selection.

```
@InProceedings{xie2022adaptive,
  title = 	 {Adaptive Inertia: Disentangling the Effects of Adaptive Learning Rate and Momentum},
  author =       {Xie, Zeke and Wang, Xinrui and Zhang, Huishuai and Sato, Issei and Sugiyama, Masashi},
  booktitle = 	 {Proceedings of the 39th International Conference on Machine Learning},
  pages = 	 {24430--24459},
  year = 	 {2022}
  volume = 	 {162},
  series = 	 {Proceedings of Machine Learning Research}
}
```



