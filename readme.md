# opt for ml

## icml 19
- [Differentiable Linearized ADMM](http://proceedings.mlr.press/v97/xie19c/xie19c.pdf)
    - By Zhouchen Lin's student
    - About ADMM-net, which uses a deep network to solve a admm alg problem.

- [Acceleration of SVRG and Katyusha X by Inexact Preconditioning](http://proceedings.mlr.press/v97/liu19a/liu19a.pdf)
  - By Wotao Yin's student
  - Using inexact preconditioning tech to accelerate SVRG and Katyusha.
  - Pros: can make svrg and katyusha very fast. The tech may also work for other schemes.
  - Cons: A step in the alg may be diffcult to be calculated.

- [Feature Grouping as a Stochastic Regularizer
for High-Dimensional Structured Data](http://proceedings.mlr.press/v97/aydore19a/aydore19a.pdf)
    - plan to read

- [Adaptive Antithetic Sampling for Variance Reduction](http://proceedings.mlr.press/v97/ren19b/ren19b.pdf)
  - Using antithetic sampling to reduce variance
  - plan to read 

- [Error Feedback Fixes SignSGD and other Gradient Compression Schemes](http://proceedings.mlr.press/v97/karimireddy19a/karimireddy19a.pdf)

- [Simple Stochastic Gradient Methods for Non-Smooth Non-Convex Regularized Optimization](http://proceedings.mlr.press/v97/metel19a/metel19a.pdf)

- [DoubleSqueeze: Parallel Stochastic Gradient Descent with Double-pass Error-Compensated Compression](http://proceedings.mlr.press/v97/tang19d/tang19d.pdf)
  
<!--
- [Faster Stochastic Alternating Direction Method of Multipliers for Nonconvex Optimization](http://proceedings.mlr.press/v97/huang19a/huang19a.pdf)

- [Riemannian adaptive stochastic gradient algorithms on matrix manifolds](http://proceedings.mlr.press/v97/kasai19a/kasai19a.pdf)

- [Stochastic Gradient Push for Distributed Deep Learning](http://proceedings.mlr.press/v97/assran19a/assran19a.pdf)

- [Decentralized Stochastic Optimization and Gossip Algorithms with Compressed Communication](http://proceedings.mlr.press/v97/koloskova19a/koloskova19a.pdf)

- [Estimate Sequences for Variance-Reduced Stochastic Composite Optimization](http://proceedings.mlr.press/v97/kulunchakov19a/kulunchakov19a.pdf)

- [On the Computation and Communication Complexity of Parallel SGD with Dynamic Batch Sizes for Stochastic Non-Convex Optimization](http://proceedings.mlr.press/v97/yu19c/yu19c.pdf)

- [On the Linear Speedup Analysis of Communication Efficient Momentum SGD for Distributed Non-Convex Optimization](http://proceedings.mlr.press/v97/yu19d/yu19d.pdf)

- [Lower Bounds for Smooth Nonconvex Finite-Sum Optimization](http://proceedings.mlr.press/v97/zhou19b/zhou19b.pdf)

- [SGD without Replacement: Sharper Rates for General Smooth Convex Functions](http://proceedings.mlr.press/v97/nagaraj19a/nagaraj19a.pdf)

-->

## icml 18
- [Katyusha X: Simple Momentum Method for Stochastic Sum-of-Nonconvex Optimization](http://proceedings.mlr.press/v80/allen-zhu18a/allen-zhu18a.pdf)
  - by Allen zhu

- [Dissecting Adam: The Sign, Magnitude and Variance of Stochastic Gradients](http://proceedings.mlr.press/v80/balles18a/balles18a.pdf)

- [SADAGRAD: Strongly Adaptive Stochastic Gradient Methods](http://proceedings.mlr.press/v80/chen18m/chen18m.pdf)

<!--

- [Dissipativity Theory for Accelerating Stochastic Variance Reduction: A Unified Analysis of SVRG and Katyusha Using Semidefinite Programs](http://proceedings.mlr.press/v80/hu18b/hu18b.pdf)
  
- [Asynchronous Decentralized Parallel Stochastic Gradient Descent](http://proceedings.mlr.press/v80/lian18a/lian18a.pdf)

- [Fast Variance Reduction Method with Stochastic Batch Size](http://proceedings.mlr.press/v80/liu18f/liu18f.pdf)
  - considers the cache/disk IO effect in saga alg.

- [Error Compensated Quantized SGD and its Applications to Large-scale Distributed Optimization](http://proceedings.mlr.press/v80/wu18d/wu18d.pdf)

-->

## icml 17

- [SARAH: A Novel Method for Machine Learning Problems Using Stochastic Recursive Gradient](http://proceedings.mlr.press/v70/nguyen17b/nguyen17b.pdf)
  - a variance reduction method, complement to svrg, saga

- [Stochastic Convex Optimization: Faster Local Growth Implies Faster Global Convergence](http://proceedings.mlr.press/v70/xu17a/xu17a.pdf)
  - promote sgd's rate

## nips 18

- [How To Make the Gradients Small Stochastically: Even Faster Convex and Nonconvex SGD](https://papers.nips.cc/paper/7392-how-to-make-the-gradients-small-stochastically-even-faster-convex-and-nonconvex-sgd)
  - By allen zhu
  - add an l_2 norm to make sgd faster

- [The Lingering of Gradients: How to Reuse Gradients Over Time](https://papers.nips.cc/paper/7400-the-lingering-of-gradients-how-to-reuse-gradients-over-time)
  - By allen zhu
  - reuse old gradients
  - an instructive paper

# Compression and Acceleration of DNN

## icml 19

- [LegoNet: Efficient Convolutional Neural Networks with Lego Filters](http://proceedings.mlr.press/v97/yang19c/yang19c.pdf)
  - consider a convolution kernel as a composition of some small basis, how to composite and the value of these basis are learnt.
  - pros: a novel idea
  - cons: the design lacks intrinsic explanation.

- [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](http://proceedings.mlr.press/v97/tan19a/tan19a.pdf)
  - By Google

- [Same, Same But Different: Recovering Neural Network Quantization Error Through Weight Factorization](http://proceedings.mlr.press/v97/meller19a/meller19a.pdf)

- [Lossless or Quantized Boosting with Integer Arithmetic](http://proceedings.mlr.press/v97/nock19a/nock19a.pdf)


- [Improving Neural Network Quantization without Retraining using Outlier Channel Splitting](http://proceedings.mlr.press/v97/zhao19c/zhao19c.pdf)

<!--

- [Towards Understanding Knowledge Distillation](http://proceedings.mlr.press/v97/phuong19a/phuong19a.pdf)

-->

- [SWALP: Stochastic Weight Averaging in Low-Precision Training](http://proceedings.mlr.press/v97/yang19d/yang19d.pdf)

- [LIT: Learned Intermediate Representation Training for Model Compression](http://proceedings.mlr.press/v97/koratana19a/koratana19a.pdf)
  - a knowledge distill method

## icml 18

- [Weightless: Lossy weight encoding for deep neural network compression](http://proceedings.mlr.press/v80/reagan18a/reagan18a.pdf)

## nips 18
- [Moonshine: Distilling with Cheap Convolutions](https://papers.nips.cc/paper/7553-moonshine-distilling-with-cheap-convolutions.pdf)
