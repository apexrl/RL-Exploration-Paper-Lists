# RL-Exploration-Paper-Lists

Paper Collection of Reinforcement Learning Exploration covers exploration of Muti-Arm-Bandit, Reinforcement Learning and Multi-agent Reinforcement Learning. 

Exploration Reinforcement Learning is an important topic in Reinforcement Learning research area, which is to essentially improve the sample efficiency in a MDP setting. Naive survey slides and documentation of exploration problem can be seen at [here](http://minghuanliu.com/talks/2019-5-8-Exploration-for-RL).

A simple form of exploration-exploitation dilemma can be seen from the Multi-Arm Bandit problems, and we include MAB papers because many theoretical idea can be drived from MAB studies. 

In the early stage, most exploration study focus on the sample efficiency of specific algorithm, many of them design different exploration bonus to lead agents explore sufficient trajectories.

Recently, most DRL exploration researches are focus on sparse reward settings and the target is a little different with the former studies, however we still classify those methods based on their methodology.

Many learning algorithm also consider the problem of efficient exploration so that we also contain such work.

Exploration is a big topic so the paper is just a scratch. Collected papers are sorted by time and classification. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact me (Email: ericliuof97 [AT] gmail.com).

## MAB exploration

### Decaying parameter

* <[A contextual-bandit algorithm for mobile context-aware recommender system](http://www.academia.edu/download/30568507/iconip.pdf)> by Djallel Bouneffouf, Amel Bouzeghoub, and Alda Lopes Gançarski, 2012.

* <[Value-difference based exploration: adaptive control between epsilon-greedy and softmax](https://pdfs.semanticscholar.org/acff/a6cd58fa6a686592c465cb8ecda4534c3664.pdf)> by Michel Tokic and Günther Palm, 2011.

* <[Adaptive ε-greedy exploration in reinforcement learning based on value differences](http://www.academia.edu/download/30819323/AdaptiveEpsilonGreedyExploration.pdf)> by Michel Tokic, 2010.


* <[Finite-time regret bounds for the multiarmed bandit problem](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.57.4710&rep=rep1&type=pdf)> by Nicolo Cesa-Bianchi and Paul Fischer, 1998.

### Provable Algorithms

* [POKER] <[Multi-armed bandit algorithms and empirical evaluation](https://link.springer.com/content/pdf/10.1007/11564096_42.pdf)> by Joannes Vermorel and Mehryar Mohri, 2005

* [UCB] <[Finite-time analysis of the multiarmed bandit problem](https://link.springer.com/content/pdf/10.1023/A:1013689704352.pdf)> by Peter Auer, Nicolo Cesa-Bianchi, and Paul Fischer, 2002.

* **[Pursuit]** <[A class of rapidly converging algorithms for learning automata]()> by MAL Thathachar, 1984.

* **[Beyesian UCB]** <[]()> by , 

## RL exploration

### Reward based Exploration (Intrinsic Reward / Exploration Bonus / Surprise / Curiosity / Uncertainty)

#### Review Papers

* <[Formal Theory of Creativity, Fun, and Intrinsic Motivation (1990-2010)](https://www.ece.uvic.ca/~bctill/papers/ememcog/Schmidhuber_2010.pdf)> by Jürgen Schmidhuber, 2010.

* <[What is intrinsic motivation? A typology of computational approaches](https://www.frontiersin.org/articles/10.3389/neuro.12.006.2007)> by Pierre-Yves Oudeyer and Frederic Kaplan, 2007.


#### Counts based methods

##### PAC-MDP

* **[MBIE]** <[An empirical evaluation of interval estimation for markov decision processes](https://www.researchgate.net/profile/Michael_Littman2/publication/4114612_An_empirical_evaluation_of_interval_estimation_for_Markov_decision_processes/links/54b66cb70cf24eb34f6d19da.pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* **[MBIE, MBIE-EB]** <[A theoretical analysis of model-based interval estimation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.1496&rep=rep1&type=pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* **[R-max]** <[R-max-a general polynomial time algorithm for near-optimal reinforcement learning](http://www.jmlr.org/papers/volume3/brafman02a/brafman02a.pdf)> by Ronen I Brafman and Moshe Tennenholtz, 2002.

* <[Near-optimal reinforcement learning in polynomial time](https://link.springer.com/content/pdf/10.1023/A:1017984413808.pdf)> by Michael Kearns and Satinder Singh, 2002.

* **[MBIE]** <[Efficient model-based exploration](https://dspace.library.uu.nl/bitstream/handle/1874/25440/Wiering_98_efficientmodelbased.pdf?sequence=1)> by Marco Wiering and Jürgen Schmidhuber, 1998.


##### Beyesian Reinforcement Learning

* <[Near-bayesian exploration in polynomial time](http://robotics.stanford.edu/~ang/papers/icml09-NearBayesianExplorationPolynomialTime-full.pdf)> by J Zico Kolter and Andrew Y Ng, 2009.

##### Psudo Count

* <[Unifying count-based exploration and intrinsic motivation](http://papers.nips.cc/paper/6383-unifying-count-based-exploration-and-intrinsic-motivation.pdf)> by Marc Bellemare, Sriram Srinivasan, Georg Ostrovski, Tom Schaul, David Saxton, and Remi Munos, 2016.

* <[Count-based exploration with neural density models](https://arxiv.org/pdf/1703.01310)>by Georg Ostrovski, Marc G Bellemare, Aaron van den Oord, and Rémi Munos, 2018

##### State Representation

* <[Contingency-aware exploration in reinforcement learning](https://arxiv.org/pdf/1811.01483)> by Choi, Jongwook and Guo, Yijie and Moczulski, Marcin and Oh, Junhyuk and Wu, Neal and Norouzi, Mohammad and Lee, Honglak, 2018.

* <[# exploration: A study of count-based exploration for deep reinforcement learning](https://papers.nips.cc/paper/6868-exploration-a-study-of-count-based-exploration-for-deep-reinforcement-learning.pdf))> by Haoran Tang, Rein Houthooft, Davis Foote, Adam Stooke, OpenAI Xi Chen, Yan Duan, John Schulman, Filip DeTurck, and Pieter Abbeel, 2017.



#### Information theory based methods

##### Mutual Information

* <[Variational information maximisation for intrinsically motivated reinforcement learning](https://papers.nips.cc/paper/5668-variational-information-maximisation-for-intrinsically-motivated-reinforcement-learning.pdf)> by Shakir Mohamed and Danilo Jimenez Rezende, 2015.

* <[An information-theoretic approach to curiosity-driven reinforcement learning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.302.1588&rep=rep1&type=pdf)> by Susanne Still and Doina Precup, 2012.

##### Information Gain

* <[Vime: Variational information maximizing exploration](https://papers.nips.cc/paper/6591-vime-variational-information-maximizing-exploration.pdf)> by Rein Houthooft, Xi Chen, Yan Duan, John Schulman, Filip De Turck, and Pieter Abbeel, 2016.

#### Prediction / Prediction Error based methods

* <[Episodic curiosity through reachability](https://arxiv.org/pdf/1810.02274)> by avinov, Nikolay and Raichuk, Anton and Marinier, Raphael and Vincent, Damien and Pollefeys, Marc and Lillicrap, Timothy and Gelly, Sylvain, 2018.

* **[RND]** <[Exploration by random network distillation](https://arxiv.org/pdf/1810.12894.pdf?utm_campaign=nathan.ai%20newsletter&utm_medium=email&utm_source=Revue%20newsletter)> by Burda, Yuri and Edwards, Harrison and Storkey, Amos and Klimov, Oleg, 2018.

* <[Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355)> by Burda, Yuri and Edwards, Harri and Pathak, Deepak and Storkey, Amos and Darrell, Trevor and Efros, Alexei A, 2018.

* **[ICM]** <[Curiosity-driven exploration by self-supervised prediction](https://pathak22.github.io/noreward-rl/resources/icml17.pdf)> by Pathak, Deepak and Agrawal, Pulkit and Efros, Alexei A and Darrell, Trevor, 2017.

### Policy based Exploration

* <[Provably efficient RL with Rich Observations via Latent State Decoding](https://arxiv.org/pdf/1901.09018)> by Du, Simon S and Krishnamurthy, Akshay and Jiang, Nan and Agarwal, Alekh and Dudik, Miroslav and Langford, John, 2019.

* <[Parameter Space Noise for Exploration](https://arxiv.org/pdf/1706.01905)> by Plappert, Matthias and Houthooft, Rein and Dhariwal, Prafulla and Sidor, Szymon and Chen, Richard Y and Chen, Xi and Asfour, Tamim and Abbeel, Pieter and Andrychowicz, Marcin, 2018.

* **[SoftAC]** <[Soft actor-critic: Off-policy maximum entropy deep reinforcement learning with a stochastic actor](https://arxiv.org/pdf/1801.01290)> by Haarnoja, Tuomas and Zhou, Aurick and Abbeel, Pieter and Levine, Sergey, 2018.

* **[SoftQ]** <[Reinforcement learning with deep energy-based policies](https://arxiv.org/pdf/1702.08165)> by Haarnoja, Tuomas and Tang, Haoran and Abbeel, Pieter and Levine, Sergey, 2017.

* <[Deep exploration via bootstrapped DQN](https://papers.nips.cc/paper/6501-deep-exploration-via-bootstrapped-dqn.pdf)> by Osband, Ian and Blundell, Charles and Pritzel, Alexander and Van Roy, Benjamin, 2016.

* <[Taming the noise in reinforcement learning via soft updates](https://arxiv.org/pdf/1512.08562)> by Fox, Roy and Pakman, Ari and Tishby, Naftali, 2015.

### Search Exploration

* **[UCT]** <[Monte-Carlo exploration for deterministic planning](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI-09/paper/viewPaper/470)> by Hootan Nakhost and Martin Müller, 2009

* <[Bandit based monte-carlo planning](https://link.springer.com/content/pdf/10.1007/11871842_29.pdf)> by Levente Kocsis and Csaba Szepesvári, 2006


### Others

* **[Go-Explore]** <[Go-Explore: a New Approach for Hard-Exploration Problems](https://arxiv.org/pdf/1901.10995)> by Ecoffet, Adrien and Huizinga, Joost and Lehman, Joel and Stanley, Kenneth O and Clune, Jeff, 2019.

## MARL exploration

* <[CLEANing the reward: counterfactual actions to remove exploratory action noise in multiagent learning](http://irll.eecs.wsu.edu/wp-content/papercite-data/pdf/2014iat-holmesparker.pdf)> by HolmesParker C, Taylor M E, Agogino A, et al. AAMAS, 2014.

* <[Classes of multiagent q-learning dynamics with epsilon-greedy exploration](http://icml2010.haifa.il.ibm.com/papers/191.pdf)> by Wunder M, Littman M L, Babes M. ICML, 2010.
