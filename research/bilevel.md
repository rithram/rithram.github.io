# Bilevel Optimization

Given some variable $$x \in X$$ and $$y \in Y$$ and functions $$f, g: X \times Y \to \mathbb{R}$$, bilevel optimization is written as the following optimization problem:

$$
\min_{x \in X} f(x, y^\star(x)) \quad \text{ subject to } \quad y^\star(x) \in \arg \min_{y \in Y} g(x, y).
$$

Stochastic bilevel optimization pertains to the case where the functions $$f,g$$ are stochastic functions with stochastic oracles $$\xi$$ and $$\psi$$ such that

$$
f(x, y) \triangleq \mathbb{E}_{\xi} F(x, y; \xi), \quad g(x, y) \triangleq \mathbb{E}_{\psi} G(x, y; \psi),
$$

which is common in AI/ML where the functions $$F, G$$ are training/validation losses on some batch of the data.



## Conference

- Ram, P., Gray, A. G., Samulowitz, H. C., & Bramble, G. (2023). **Toward Theoretical Guidance for Two Common Questions in Practical Cross-Validation based Hyperparameter Selection**. *SIAM Internation Conference on Data Mining*. [arXiv](https://arxiv.org/pdf/2301.05131.pdf), [paper](https://epubs.siam.org/doi/10.1137/1.9781611977653.ch90)

- Gu, A., Lu, S., Ram, P., & Weng, L. (2022). **Min-max Bilevel Multi-objective Optimization with Applications in Machine Learning**. *International Conference in Learning Representations*. [arXiv](https://arxiv.org/pdf/2203.01924.pdf) [OpenReview](https://openreview.net/forum?id=PvDY71zKsvP)

- Zhou, Y., Ram, P., Salonidis, T., Baracaldo, N., Samulowitz, H., & Ludwig, H. (2022). **Single-shot Hyper-parameter Optimization for Federated Learning: A General Algorithm & Analysis**. *International Conference in Learning Representations*. [arXiv](https://arxiv.org/pdf/2202.08338.pdf) [OpenReview](https://openreview.net/forum?id=3RhuF8foyPW)  [slides](./papers/2023/ZRSBSL_ICLR23.slides.pdf) **(notable-top-25%)**

- Zhang, Y., Sharma, P., Ram, P., Hong, M., Varshney, K. R., & Liu, S. (2023) **What Is Missing in IRM Training and Evaluation? Challenges and Solutions**. *International Conference in Learning Representations*. [arXiv](https://arxiv.org/pdf/2303.02343.pdf) [OpenReview](https://openreview.net/forum?id=MjsDeTcDEy)

- Zhang, Y., Yao, Y., Ram, P., Zhao, P., Chen, T., Hong, M. & Liu, S. (2022). **Advancing Model Pruning via Bi-level Optimization**. *Annual Conference on Neural Information Processing Systems*. [arXiv](https://arxiv.org/pdf/2210.04092.pdf) [OpenReview](https://openreview.net/forum?id=t6O08FxvtBY)

- Gu, A., Lu, S., **Ram, P.**, & Weng, L. (2022). **Robust Multi-objective Bilevel Optimization With Applications In Machine Learning**. *INFORMS Annual Meeting*. [webpage](https://research.ibm.com/publications/robust-multi-objective-bilevel-optimization-with-applications-in-machine-learning) [slides](./papers/2022/GLRW_INFORMS22.pdf)

- Teng, Y., Choromanska, A., Campbell, M., Lu, S., Ram, P., & Horesh, L. (2022). **Overcoming Catastrophic Forgetting via Direction-Constrained Optimization**. *European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases*. [paper](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_1288.pdf)

- Zhao, P., Ram, P., Lu, S., Yao, Y., Bouneffouf, D., Lin, X., & Liu, S. (2022). **Learning to Generate Image Source-Agnostic Universal Adversarial Perturbations**. *International Joint Conference on Artificial Intelligence*. [paper](https://www.ijcai.org/proceedings/2022/0239.pdf) [arXiv](https://arxiv.org/pdf/2009.13714.pdf)


## Workshop

- Fan, C., Ram, P., & Liu, S. (2021). **Sign-MAML: Efficient Model-Agnostic Meta-Learning by SignSGD**. *5th Workshop on Meta-Learning at NeurIPS 2021* [arXiv](https://arxiv.org/pdf/2109.07497.pdf)

- Gu, A., Lu, S., Ram, P., and Weng, T.-W. (2021). **Nonconvex min-max bilevel optimization for task robust meta learning**. *Beyond first order methods in machine learning systems* at ICML 2021. [paper](https://drive.google.com/file/d/1JkLOYmAERWUKBvXg1G0j1N6Vf-rKNk5z/view?usp=sharing)
