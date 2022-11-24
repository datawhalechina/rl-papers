## Paper Collection of RL basics

### Review papers

* Offline RL: [A Survey on Offline Reinforcement Learning: Taxonomy, Review, and Open Problems](https://arxiv.org/abs/2203.01387), Rafael Figueiredo Prudencio et al, 2022

### DQN Related

* DQN: [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/pdf/1312.5602v1.pdf), V.Mnih et al 2013.

  > Typical DQN paper

* DQN: [Human-level control through deep reinforcement learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf), V.Mnih et al 2015, Nature.

  > Narture DQN, Compared to typical DQN paper, proposes a periodically updated target Q to address instabilities, which is more common today

* DoubleDQN: [Deep Reinforcement Learning with Double Q-Learning](https://ojs.aaai.org/index.php/AAAI/article/view/10295), H Van Hasselt et al 2016, AAAI.

* DuelingDQN: [Dueling Network Architectures for Deep Reinforcement Learning](http://proceedings.mlr.press/v48/wangf16.pdf), Z Wang et al 2015.

* PER: [Prioritized Experience Replay](https://arxiv.org/pdf/1511.05952.pdf), T Schaul et al 2015, ICLR.

* Rainbow DQN: [Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/pdf/1710.02298.pdf), M Hessel et al 2017, AAAI.

* DRQN: [Deep Recurrent Q-Learning for Partially Observable MDPs](https://www.aaai.org/ocs/index.php/FSS/FSS15/paper/view/11673/11503), M Hausknecht e al 2015, AAAI.

* Noisy DQN: [Noisy Networks for Exploration](https://arxiv.org/pdf/1706.10295.pdf), M Fortunato et al 2017, ICLR.

* Averaged-DQN: [Averaged-DQN: Variance Reduction and Stabilization for Deep Reinforcement Learning](http://proceedings.mlr.press/v70/anschel17a/anschel17a.pdf), O Anschel et al 2016, ICML.

* C51: [A Distributional Perspective on Reinforcement Learning](https://arxiv.org/abs/1707.06887), 2017, ICML

* [Neural Network Dynamics for Model-Based Deep Reinforcement Learning with Model-Free Fine-Tuning](https://arxiv.org/pdf/1708.02596.pdf),A Nagabandi et al 2017, ICRA.

* [Deep Reinforcement Learning and the Deadly Triad](https://arxiv.org/pdf/1812.02648.pdf), H. V. Hasselt et al 2018.

### Policy gradient and related

* REINFORCE: [Policy Gradient  Methods for  Reinforcement  Learning with Function  Approximation](https://proceedings.neurips.cc/paper/1999/file/464d828b85b0bed98e80ade0a5c43b0f-Paper.pdf), Sutton et al, 1999, NIPS
* A3C: [Asynchronous Methods for Deep Reinforcement Learning](http://proceedings.mlr.press/v48/mniha16.pdf), Mnig et al, 2016, ICML.
* TRPO: [Trust Region Policy Optimization](http://proceedings.mlr.press/v37/schulman15.pdf), J. Schulman et al 2015, ICML.
* GAE: [High-Dimensional Continuous Control Using Generalized Advantage Estimation](https://arxiv.org/pdf/1506.02438.pdf), J. Schulman et al 2015, ICLR.
* PPO: [Proximal Policy Optimization Algorithms](https://arxiv.org/pdf/1707.06347.pdf), J. Schulman et al 2017.
* [Emergence of Locomotion Behaviours in Rich Environments](https://arxiv.org/pdf/1707.02286.pdf), N. Heess et al 2017.
* ACKTR: [Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation](https://proceedings.neurips.cc/paper/2017/file/361440528766bbaaaa1901845cf4152b-Paper.pdf), Y Wu et al 2017, NIPS.
* ACER: [Sample Efficient Actor-Critic with Experience Replay](https://arxiv.org/pdf/1611.01224.pdf), Z Wang et al 2016, ICLR.
* DPG: [Deterministic Policy Gradient Algorithms](http://proceedings.mlr.press/v32/silver14.pdf), D Silver et al 2014, ICML.
* DDPG: [Continuous control with deep reinforcement learning](https://arxiv.org/pdf/1509.02971.pdf), TP Lillicrap et al 2016, ICLR.
* TD3: [Addressing Function Approximation Error in Actor-Critic Methods](http://proceedings.mlr.press/v80/fujimoto18a/fujimoto18a.pdf), S Fujimoto et al 2018, ICML.
* C51: [A Distributional Perspective on Reinforcement Learning](http://proceedings.mlr.press/v70/bellemare17a/bellemare17a.pdf), MG Bellemare et al 2017, ICML.
* Q-Prop:[Q-Prop: Sample-Efficient Policy Gradient with An Off-Policy Critic](https://arxiv.org/pdf/1611.02247.pdf), S Gu et al 2016, ICLR.
* [Action-dependent Control Variates for Policy Optimization via Stein’s Identity](https://arxiv.org/pdf/1710.11198.pdf), H Liu et al 2017, ICLR.
* [The Mirage of Action-Dependent Baselines in Reinforcement Learning](http://proceedings.mlr.press/v80/tucker18a/tucker18a.pdf), G Tucker et al 2018, ICML.
* PCL:[Bridging the Gap Between Value and Policy Based Reinforcement Learning](https://proceedings.neurips.cc/paper/2017/file/facf9f743b083008a894eee7baa16469-Paper.pdf), O Nachum et al 2017, NIPS.
* Trust-PCL:[Trust-PCL: An Off-Policy Trust Region Method for Continuous Control](https://arxiv.org/pdf/1707.01891.pdf), O Nachum et al 2017, CoRR.
* PGQL:[Combining Policy Gradient and Q-learning](https://arxiv.org/pdf/1611.01626.pdf), B O'Donoghue et al 2016, ICLR.
* [The Reactor: A Fast and Sample-Efficient Actor-Critic Agent for Reinforcement Learning](https://arxiv.org/pdf/1704.04651.pdf), A Gruslys et al 2017, ICLR.
* IPG:[Interpolated Policy Gradient: Merging On-Policy and Off-Policy Gradient Estimation for Deep Reinforcement Learning](https://arxiv.org/pdf/1706.00387.pdf), S Gu et al 2017, NIPS.
* [Equivalence Between Policy Gradients and Soft Q-Learning](https://arxiv.org/pdf/1704.06440.pdf), J Schulman et al 2017.
* IQN:[Implicit Quantile Networks for Distributional Reinforcement Learning](http://proceedings.mlr.press/v80/dabney18a/dabney18a.pdf), W Dabney et al 2018, ICML.
* [Dopamine: A Research Framework for Deep Reinforcement Learning](https://arxiv.org/pdf/1812.06110.pdf), PS Castro et al 2018.

### Exploration and related

* VIME:[VIME: Variational Information Maximizing Exploration](https://proceedings.neurips.cc/paper/2016/file/abd815286ba1007abfbb8415b83ae2cf-Paper.pdf), R Houthooft et al 2017, NIPS.
* [Unifying Count-Based Exploration and Intrinsic Motivation](https://proceedings.neurips.cc/paper/2016/file/afda332245e2af431fb7b672a68b659d-Paper.pdf), MG Bellemare et al 2016, NIPS.
* [Count-Based Exploration with Neural Density Models](http://proceedings.mlr.press/v70/ostrovski17a/ostrovski17a.pdf), G Ostrovski et al 2017, ICML.
* [#Exploration: A Study of Count-Based Exploration for Deep Reinforcement Learning](https://proceedings.neurips.cc/paper/2017/file/3a20f62a0af1aa152670bab3c602feed-Paper.pdf), H Tang et al 2016, NIPS. 
* EX2:[EX2: Exploration with Exemplar Models for Deep Reinforcement Learning](https://proceedings.neurips.cc/paper/2017/file/1baff70e2669e8376347efd3a874a341-Paper.pdf), J Fu et al 2017, NIPS.
* ICM:[Curiosity-driven Exploration by Self-supervised Prediction](http://proceedings.mlr.press/v70/pathak17a/pathak17a.pdf), D Pathak et al 2017, ICML.
* [Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355.pdf), Y Burda et al 2018, ICLR.
* RND:[Exploration by Random Network Distillation](https://arxiv.org/pdf/1810.12894.pdf%20http://arxiv.org/abs/1810.12894.pdf), Y Burda et al 2018, ICLR.

### Maximum Entropy RL

* SAC:[Soft Actor-Critic:Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor](http://proceedings.mlr.press/v80/haarnoja18b/haarnoja18b.pdf), T Haarnoja et al 2018, ICML.


### Distributed RL

* Distributed DQN:[Massively Parallel Methods for Deep Reinforcement Learning](https://arxiv.org/pdf/1507.04296.pdf), A Nair et al 2015.
* [Distributed Prioritized Experience Replay](https://arxiv.org/pdf/1803.00933.pdf), D Horgan et al 2018, ICLR.
* QR-DQN:[Distributional Reinforcement Learning with Quantile Regression](https://ojs.aaai.org/index.php/AAAI/article/view/11791), W Dabney et al 2017, AAAI.


### Offline RL

* REM: [An Optimistic Perspective on Offline Reinforcement Learning](https://arxiv.org/abs/1907.04543), Rishabh Agarwal et al 2016.
* AWR: [Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/abs/1910.00177), Xue Bin Peng et al 2019, CoRR.
* AWAC: [AWAC: Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359), Ashvin Nair et al 2020, CoRR
* TD3+BC: [A Minimalist Approach to Offline Reinforcement Learning](https://arxiv.org/abs/2106.06860), Scott Fujimoto et al 2020.
* CQL: [Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2006.04779), Aviral Kumar et al 2020, CoRR.
* IQL: [Offline Reinforcement Learning with Implicit Q-Learning](https://arxiv.org/abs/2110.06169), Ilya Kostrikov et al 2021.

## Refs

* https://spinningup.openai.com/en/latest/spinningup/keypapers.html
