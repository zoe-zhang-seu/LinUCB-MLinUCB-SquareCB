This is an implementation of multi-arm bandit model by python. Multi-armed bandits (MABs) are a simple yet powerful framework for sequential decision-making under uncertainty.
### Tasks

1.LinUCB
- [x] Implement LinUCB model
- [x] Run offline evaluation and plot the per-round cumulative reward with `matplotlib.pyplot`
- [x] Tune MAB’s hyperparameters. Devise and run a grid-search based strategy to select **alpha** for LinUCB 

2.MLinUCB
- [x] Implement MLinCB model
- [x] Tuning **alpha**, **N** and **m**

3.SquareCB
- [x] Implement SquareCB model
- [x] Tuning **gamma**
 
### Output image

![model performance](https://github.com/zoe-zhang-seu/LinUCB-MLinUCB-SquareCB/blob/main/performance%20comparison.png)

---

### Reference:

**LinUCB model**

- *Lihong Li, Wei Chu, John Langford, Robert E. Schapire, ‘A Contextual-Bandit Approach to Per- sonalized News Article Recommendation’, in Proceedings of the Nineteenth International Conference on World Wide Web (WWW’2010), Raleigh, NC, USA, 2010.*

- [LinUCB paper link](https://arxiv.org/pdf/1003.0146.pdf)

**MLinUCB model**

- *Djallel Bouneffouf, Sohini Upadhyay, and Yasaman Khazaeni. ‘Contextual Bandit with Missing Rewards.’ arXiv:2007.06368 [cs.LG]. 2020.*

- [MLinUCB paper link](https://arxiv.org/pdf/2007.06368.pdf)

**SquareCB model**

- *Dylan Foster and Alexander Rakhlin. ‘Beyond UCB: Optimal and Efficient Contextual Bandits with Regression Oracles.’ In Proceedings of the 37th International Conference on Machine Learning (ICML’2020), pp. 3199-3210, PMLR, 2020.*

- [MLinUCB paper link](http://proceedings.mlr.press/v119/foster20a/foster20a.pdf)
