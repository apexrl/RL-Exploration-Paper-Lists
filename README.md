# RL-Exploration-Paper-Lists

Paper Collection of Reinforcement Learning Exploration covers exploration of Muti-Arm-Bandit, Reinforcement Learning and Multi-agent Reinforcement Learning. 

Exploration Reinforcement Learning is an important topic in Reinforcement Learning research area, which is to essentially improve the sample efficiency in a MDP setting.

A simple form of exploration-exploitation dilemma can be seen from the Multi-Arm Bandit problems, and we include MAB papers because many theoretical idea can be drived from MAB studies. 

Recently, most DRL exploration researches are focus on sparse reward settings and the target is a little different with the former studies, however we still classify those methods based on their methodology.

Papers are sorted by time and classification. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact me (Email: ericliuof97 [AT] gmail.com).

## MAB exploration

## RL exploration

### Reward based Exploration (Intrinsic Reward / Surprise / Curiosity / Uncertainty)

#### Review Papers

* <Formal Theory of Creativity, Fun, and Intrinsic Motivation (1990-2010)> by Jürgen Schmidhuber, 2010.

* <What is intrinsic motivation? A typology of computational approaches> by Pierre-Yves Oudeyer and Frederic Kaplan, 2007.


#### Counts based methods

##### PAC-MDP

* <An empirical evaluation of interval estimation for markov decision processes> by Alexander L Strehl and Michael L Littman, 2004.

* <A theoretical analysis of model- based interval estimation.> by Alexander L Strehl and Michael L Littman, 2004.

* <R-max-a general polynomial time algorithm for near-optimal reinforcement learning> by Ronen I Brafman and Moshe Tennenholtz, 2002.

* <Near-optimal reinforcement learning in polynomial time> by Michael Kearns and Satinder Singh, 2002.

* <Efficient model-based exploration> by Marco Wiering and Jürgen Schmidhuber, 1998.


##### Beyesian Reinforcement Learning

* <Near-bayesian exploration in polynomial time> by J Zico Kolter and Andrew Y Ng, 2009.

##### Psudo Count

* <Unifying count-based exploration and intrinsic motivation> by Marc Bellemare, Sriram Srinivasan, Georg Ostrovski, Tom Schaul, David Saxton, and Remi Munos, 2016.

* <Count-based exploration with neural density models>by Georg Ostrovski, Marc G Bellemare, Aaron van den Oord, and Rémi Munos, 2018

##### State Representation

* <[Contingency-aware exploration in reinforcement learning](https://arxiv.org/pdf/1811.01483)> by Choi, Jongwook and Guo, Yijie and Moczulski, Marcin and Oh, Junhyuk and Wu, Neal and Norouzi, Mohammad and Lee, Honglak, 2018.

* <[# exploration: A study of count-based exploration for deep reinforcement learning](https://papers.nips.cc/paper/6868-exploration-a-study-of-count-based-exploration-for-deep-reinforcement-learning.pdf))> by Haoran Tang, Rein Houthooft, Davis Foote, Adam Stooke, OpenAI Xi Chen, Yan Duan, John Schulman, Filip DeTurck, and Pieter Abbeel, 2017.



#### Information theory based methods

##### Mutual Information

* <Variational information maximisation for intrinsically motivated reinforcement learning> by Shakir Mohamed and Danilo Jimenez Rezende, 2015.

* <An information-theoretic approach to curiosity-driven reinforcement learning> by Susanne Still and Doina Precup, 2012.

##### Information Gain

* <Vime: Variational information maximizing exploration> by Rein Houthooft, Xi Chen, Yan Duan, John Schulman, Filip De Turck, and Pieter Abbeel, 2016.

#### Prediction Error based methods

* <[Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355)> by Burda, Yuri and Edwards, Harri and Pathak, Deepak and Storkey, Amos and Darrell, Trevor and Efros, Alexei A, 2018.

* <[Curiosity-driven exploration by self-supervised prediction](https://pathak22.github.io/noreward-rl/resources/icml17.pdf)> by Pathak, Deepak and Agrawal, Pulkit and Efros, Alexei A and Darrell, Trevor, 2017.

### Policy based Exploration

* <[Provably efficient RL with Rich Observations via Latent State Decoding](https://arxiv.org/pdf/1901.09018)> by Du, Simon S and Krishnamurthy, Akshay and Jiang, Nan and Agarwal, Alekh and Dud{\'\i}k, Miroslav and Langford, John, 2019.

* <[Parameter Space Noise for Exploration](https://arxiv.org/pdf/1706.01905)> by Plappert, Matthias and Houthooft, Rein and Dhariwal, Prafulla and Sidor, Szymon and Chen, Richard Y and Chen, Xi and Asfour, Tamim and Abbeel, Pieter and Andrychowicz, Marcin, 2018.

### Search Exploration

* <[Monte-Carlo exploration for deterministic planning](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI-09/paper/viewPaper/470)> by Hootan Nakhost and Martin Müller, 2009

* <[Bandit based monte-carlo planning](https://link.springer.com/content/pdf/10.1007/11871842_29.pdf)> by Levente Kocsis and Csaba Szepesvári, 2006

## MARL exploration
