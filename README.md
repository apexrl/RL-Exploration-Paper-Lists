# RL-Exploration-Paper-Lists

Paper Collection of Reinforcement Learning Exploration covers Exploration of Muti-Arm-Bandit, Reinforcement Learning and Multi-agent Reinforcement Learning. 

Exploration Reinforcement Learning is an important topic in Reinforcement Learning research area, which is to essentially improve the sample efficiency in a MDP setting. Naive survey [Slides](http://minghuanliu.com/files/2019-5-8-Exploration-for-RL.pdf) and [Document(Chinese)](http://minghuanliu.com/files/exploration-talk.pdf) of Exploration problem are available.

A simple form of Exploration-exploitation dilemma can be seen from the Multi-Arm Bandit problems, and we include MAB papers because many theoretical idea can be drived from MAB studies. 

In the early stage, most Exploration study focus on the sample efficiency of specific algorithm, many of them design different Exploration bonus to lead agents explore sufficient trajectories.

Recently, most DRL Exploration researches are focus on sparse reward settings and the target is a little different with the former studies, however we still classify those methods based on their methodology.

Many learning algorithm also consider the problem of efficient Exploration so that we also contain such work.

Exploration is a big topic so this paper list is just a scratch. Collected papers are sorted by time and classification. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact me (Email: ericliuof97 [AT] gmail.com).

## Overview
* [MAB Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#MAB-Exploration)
  * [MAB Review Papers](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#MAB-review-papers)
  * [Decaying Parameter](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Decaying-parameter)
  * [Provable Algorithms](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Provable-algorithms)
  * [Beyesian Bandit](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Beyesian-bandit)
  * [Gittin Indices](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Gittin-indices)
  * [Comparative Experiments](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Comparative-experiments)

* [RL Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#RL-Exploration)
  * [Reward based Exploration (Intrinsic Reward / Exploration Bonus / Surprise / Curiosity / Uncertainty)](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Reward-based-Exploration-(Intrinsic-Reward-\\-Exploration-Bonus-\\-Surprise-\\-Curiosity-\\-Uncertainty))
      * [Intrinsic reward review papers](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Intrinsic-reward-review-papers)
      * [Counts based methods](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Counts-based-methods)
      * [Information theory based methods](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Information-theory-based-methods)
      * [Prediction / Prediction Error based Methods](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Prediction-\-Prediction-error-based-methods)
  * [Policy based Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Policy-based-Exploration)
  * [Search Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Search-Exploration)
  * [Others](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Others)

* [MARL Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#MARL-Exploration)
  * [Coordinated Exploration](https://github.com/Ericonaldo/RL-Exploration-Paper-Lists#Coordinated-Exploration)

## MAB Exploration

### MAB Review Papers

* <[Bandit problems: sequential allocation of experiments (monographs on statistics and applied probability)](https://link.springer.com/content/pdf/10.1007/978-94-015-3711-7.pdf)> by Donald A Berry and Bert Fristedt, 1985.

### Decaying Parameter

* <[A contextual-bandit algorithm for mobile context-aware recommender system](http://www.academia.edu/download/30568507/iconip.pdf)> by Djallel Bouneffouf, Amel Bouzeghoub, and Alda Lopes Gançarski, 2012.

* <[Value-difference based Exploration: adaptive control between epsilon-greedy and softmax](https://pdfs.semanticscholar.org/acff/a6cd58fa6a686592c465cb8ecda4534c3664.pdf)> by Michel Tokic and Günther Palm, 2011.

* <[Adaptive ε-greedy Exploration in reinforcement learning based on value differences](http://www.academia.edu/download/30819323/AdaptiveEpsilonGreedyExploration.pdf)> by Michel Tokic, 2010.


* <[Finite-time regret bounds for the multiarmed bandit problem](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.57.4710&rep=rep1&type=pdf)> by Nicolo Cesa-Bianchi and Paul Fischer, 1998.

### Provable Algorithms

* **[POKER]** <[Multi-armed bandit algorithms and empirical evaluation](https://link.springer.com/content/pdf/10.1007/11564096_42.pdf)> by Joannes Vermorel and Mehryar Mohri, 2005

* **[UCB]** <[Finite-time analysis of the multiarmed bandit problem](https://link.springer.com/content/pdf/10.1023/A:1013689704352.pdf)> by Peter Auer, Nicolo Cesa-Bianchi, and Paul Fischer, 2002.

* **[Pursuit]** <[A class of rapidly converging algorithms for learning automata](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=A+class+of+rapidly+converging+algorithms+for+learning+automata&btnG=)> by MAL Thathachar, 1984.

#### Beyesian Bandit

* **[Beyesian UCB]** <[On bayesian up- per confidence bounds for bandit problems](http://www.jmlr.org/proceedings/papers/v22/kaufmann12/kaufmann12.pdf)> by Emilie Kaufmann, Olivier Cappé, and Aurélien Garivier, 2012.

* <[A modern bayesian look at the multi-armed bandit](https://pdfs.semanticscholar.org/0323/0c3c83dbb013c3e610702c6f650307f0ce5c.pdf)> by Steven L Scott, 2010.

#### Gittin Indices

* <[Optimal learning and experimentation in bandit problems](https://pdfs.semanticscholar.org/42e2/708e1d6c73ecef5ddc4fd7935a4f055de774.pdf)> by Monica Brezzi and Tze Leung Lai, 2002.

* <[Bandit processes and dynamic allocation indices](https://core.ac.uk/download/pdf/6519269.pdf)> by John C Gittins, 1979.

### Comparative Experiments

* **[Interesting]** <[Algorithms for multi-armed bandit problems](https://arxiv.org/pdf/1402.6028)> by Kuleshov, Volodymyr and Precup, Doina, 2014.

## RL Exploration

### Reward based Exploration (Intrinsic Reward \ Exploration Bonus \ Surprise \ Curiosity \ Uncertainty)

#### Intrinsic Reward Review Papers

* <[Formal Theory of Creativity, Fun, and Intrinsic Motivation (1990-2010)](https://www.ece.uvic.ca/~bctill/papers/ememcog/Schmidhuber_2010.pdf)> by Jürgen Schmidhuber, 2010.

* <[What is intrinsic motivation? A typology of computational approaches](https://www.frontiersin.org/articles/10.3389/neuro.12.006.2007)> by Pierre-Yves Oudeyer and Frederic Kaplan, 2007.


#### Counts based Methods

##### PAC-MDP

* **[MBIE, MBIE-EB]** <[A theoretical analysis of model-based interval estimation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.1496&rep=rep1&type=pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* **[MBIE]** <[An empirical evaluation of interval estimation for markov decision processes](https://www.researchgate.net/profile/Michael_Littman2/publication/4114612_An_empirical_evaluation_of_interval_estimation_for_Markov_decision_processes/links/54b66cb70cf24eb34f6d19da.pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* **[R-max]** <[R-max-a general polynomial time algorithm for near-optimal reinforcement learning](http://www.jmlr.org/papers/volume3/brafman02a/brafman02a.pdf)> by Ronen I Brafman and Moshe Tennenholtz, 2002.

* **[E3]** <[Near-optimal reinforcement learning in polynomial time](https://link.springer.com/content/pdf/10.1023/A:1017984413808.pdf)> by Michael Kearns and Satinder Singh, 2002.

* **[MBIE]** <[Efficient model-based Exploration](https://dspace.library.uu.nl/bitstream/handle/1874/25440/Wiering_98_efficientmodelbased.pdf?sequence=1)> by Marco Wiering and Jürgen Schmidhuber, 1998.


##### Beyesian Reinforcement Learning

* <[Near-bayesian Exploration in polynomial time](http://robotics.stanford.edu/~ang/papers/icml09-NearBayesianExplorationPolynomialTime-full.pdf)> by J Zico Kolter and Andrew Y Ng, 2009.

##### Psudo Count

* <[Unifying count-based Exploration and intrinsic motivation](http://papers.nips.cc/paper/6383-unifying-count-based-Exploration-and-intrinsic-motivation.pdf)> by Marc Bellemare, Sriram Srinivasan, Georg Ostrovski, Tom Schaul, David Saxton, and Remi Munos, 2016.

* <[Count-based Exploration with neural density models](https://arxiv.org/pdf/1703.01310)>by Georg Ostrovski, Marc G Bellemare, Aaron van den Oord, and Rémi Munos, 2018

##### State Representation

* **[CoEX]** <[Contingency-aware Exploration in reinforcement learning](https://arxiv.org/pdf/1811.01483)> by Choi, Jongwook and Guo, Yijie and Moczulski, Marcin and Oh, Junhyuk and Wu, Neal and Norouzi, Mohammad and Lee, Honglak, 2018.

* <[# Exploration: A study of count-based Exploration for deep reinforcement learning](https://papers.nips.cc/paper/6868-Exploration-a-study-of-count-based-Exploration-for-deep-reinforcement-learning.pdf)> by Haoran Tang, Rein Houthooft, Davis Foote, Adam Stooke, OpenAI Xi Chen, Yan Duan, John Schulman, Filip DeTurck, and Pieter Abbeel, 2017.



#### Information Theory based Methods

##### Mutual Information

* <[Variational information maximisation for intrinsically motivated reinforcement learning](https://papers.nips.cc/paper/5668-variational-information-maximisation-for-intrinsically-motivated-reinforcement-learning.pdf)> by Shakir Mohamed and Danilo Jimenez Rezende, 2015.

* <[An information-theoretic approach to curiosity-driven reinforcement learning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.302.1588&rep=rep1&type=pdf)> by Susanne Still and Doina Precup, 2012.

##### Information Gain

* <[Vime: Variational information maximizing Exploration](https://papers.nips.cc/paper/6591-vime-variational-information-maximizing-Exploration.pdf)> by Rein Houthooft, Xi Chen, Yan Duan, John Schulman, Filip De Turck, and Pieter Abbeel, 2016.

#### Prediction / Prediction error based Methods


* <[Self-Supervised Exploration via Disagreement](https://pathak22.github.io/exploration-by-disagreement/resources/icml19.pdf)> by Deepak Pathak, Dhiraj Gandhi and Abhinav Gupta, 2019.

* <[Episodic curiosity through reachability](https://arxiv.org/pdf/1810.02274)> by Savinov, Nikolay and Raichuk, Anton and Marinier, Raphael and Vincent, Damien and Pollefeys, Marc and Lillicrap, Timothy and Gelly, Sylvain, 2018.

* **[RND]** <[Exploration by random network distillation](https://arxiv.org/pdf/1810.12894.pdf?utm_campaign=nathan.ai%20newsletter&utm_medium=email&utm_source=Revue%20newsletter)> by Burda, Yuri and Edwards, Harrison and Storkey, Amos and Klimov, Oleg, 2018.

* <[Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355)> by Burda, Yuri and Edwards, Harri and Pathak, Deepak and Storkey, Amos and Darrell, Trevor and Efros, Alexei A, 2018.

* **[ICM]** <[Curiosity-driven Exploration by self-supervised prediction](https://pathak22.github.io/noreward-rl/resources/icml17.pdf)> by Pathak, Deepak and Agrawal, Pulkit and Efros, Alexei A and Darrell, Trevor, 2017.

### Policy based Exploration

* <[Provably efficient RL with Rich Observations via Latent State Decoding](https://arxiv.org/pdf/1901.09018)> by Du, Simon S and Krishnamurthy, Akshay and Jiang, Nan and Agarwal, Alekh and Dudik, Miroslav and Langford, John, 2019.

* <[Parameter Space Noise for Exploration](https://arxiv.org/pdf/1706.01905)> by Plappert, Matthias and Houthooft, Rein and Dhariwal, Prafulla and Sidor, Szymon and Chen, Richard Y and Chen, Xi and Asfour, Tamim and Abbeel, Pieter and Andrychowicz, Marcin, 2018.

* **[SoftAC]** <[Soft actor-critic: Off-policy maximum entropy deep reinforcement learning with a stochastic actor](https://arxiv.org/pdf/1801.01290)> by Haarnoja, Tuomas and Zhou, Aurick and Abbeel, Pieter and Levine, Sergey, 2018.

* **[SoftQ]** <[Reinforcement learning with deep energy-based policies](https://arxiv.org/pdf/1702.08165)> by Haarnoja, Tuomas and Tang, Haoran and Abbeel, Pieter and Levine, Sergey, 2017.

* <[Deep Exploration via bootstrapped DQN](https://papers.nips.cc/paper/6501-deep-Exploration-via-bootstrapped-dqn.pdf)> by Osband, Ian and Blundell, Charles and Pritzel, Alexander and Van Roy, Benjamin, 2016.

* <[Taming the noise in reinforcement learning via soft updates](https://arxiv.org/pdf/1512.08562)> by Fox, Roy and Pakman, Ari and Tishby, Naftali, 2015.

### Search Exploration

* **[UCT]** <[Monte-Carlo Exploration for deterministic planning](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI-09/paper/viewPaper/470)> by Hootan Nakhost and Martin Müller, 2009

* <[Bandit based monte-carlo planning](https://link.springer.com/content/pdf/10.1007/11871842_29.pdf)> by Levente Kocsis and Csaba Szepesvári, 2006


### Others

* **[Go-Explore]** <[Go-Explore: a New Approach for Hard-Exploration Problems](https://arxiv.org/pdf/1901.10995)> by Ecoffet, Adrien and Huizinga, Joost and Lehman, Joel and Stanley, Kenneth O and Clune, Jeff, 2019.

## MARL Exploration

* <[CLEANing the reward: counterfactual actions to remove exploratory action noise in multiagent learning](http://irll.eecs.wsu.edu/wp-content/papercite-data/pdf/2014iat-holmesparker.pdf)> by HolmesParker C, Taylor M E, Agogino A, et al., 2014.

* <[Classes of multiagent q-learning dynamics with epsilon-greedy Exploration](http://icml2010.haifa.il.ibm.com/papers/191.pdf)> by Wunder M, Littman M L, Babes M., 2010.

## Coordinated Exploration

* <[Coordinated Exploration via Intrinsic Rewards for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1905.12127)> by Shariq Iqbal, Fei Sha, 2019.

* <[Coordinated Versus Decentralized Exploration In Multi-Agent Multi-Armed Bandits](https://arxiv.org/abs/1905.12127)> by Mithun Chakraborty, Kai Yee Phoebe Chua, Sanmay Das, Brendan Juba, 2017.

* <[Multi-Robot Coordination for Space Exploration](https://pdfs.semanticscholar.org/bd5a/9db1b2643cf1e7cdf6be43d8e64dc535c1ce.pdf)> by Logan Yliniemi and Adrian Agogino and Kagan Tumer, 2013.

* <[Coordinated Multi-Agent Exploration](http://ceur-ws.org/Vol-408/Paper08.pdf)> by Abraham Sanchez L. and Alfredo Toriz P., 2008.

* <[Coordinated exploration in multi-agent reinforcement learning: an application to load-balancing](https://www.researchgate.net/publication/221454629_Coordinated_exploration_in_multi-agent_reinforcement_learning_an_application_to_load-balancing)> by Katja Verbeeck, Ann Nowe and Karl Tuyls, 2005.


