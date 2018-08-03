# Awesome Multi-Objective Optimization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome multi-objective optimization research resources. Inspired by [awesome-360-vision](https://github.com/hsientzucheng/awesome-360-vision), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning) and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers). Still working on it, any suggestions of missing reference are welcome.


## Table of Contents

- [Papers](#papers)
  - [Reinforcement Learning](#reinforcement-learning)
    - [Single Policy](#single-policy)
    - [Multiple Policy](#multiple-policy)
  - [Evolutionary Algorithms](#evolutionary-algorithms)
    - [Dominance Based](#dominance-based)
    - [Aggregation Based](#aggregation-based)
    - [Indicator Based](#indicator-based)
  - [Gradient Based](#gradient-based)
  - [Others](#others)
- [Libraries](#libraries)
- [Benchmarks](#benchmarks)
- [Talks](#communities)



## Papers

### Reinforcement Learning
#### Survey
- A survey of multi-objective sequential decision-making. [[pdf]](https://arxiv.org/pdf/1402.0590) 
  - Roijers, Diederik M., et al. *JAIR 2013*
- Multiobjective reinforcement learning: A comprehensive overview. [[pdf]](https://arxiv.org/pdf/1402.0590) 
  - C. Liu, X. Xu, D. Hu *IEEE SMC 2015*

#### Single Policy
##### Weighted-Sum Approach
- Learning to solve multiple goals. [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.37.8338&rep=rep1&type=pdf) 
  - J. Karlsson.
- Multiple-goal reinforcement learning with modular sarsa (0). [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.37.8338&rep=rep1&type=pdf)
  - N. Sprague, D. Ballard. *IJCAI 2003*
- A multiple goal reinforcement learn-ing method for complex vehicle overtaking maneuver. [[pdf]](https://hub.hku.hk/bitstream/10722/137287/1/Content.pdf?accept=1)
  - DCK Ngai, NHC Yung. *WCICA 2010*
- Self-adaptive multi-objective optimization method design based on agent reinforcement learning for elevator group control systems. [[pdf]](https://ieeexplore.ieee.org/abstract/document/5554696/)
  - F. Zeng, Q. Zong, Z. Sun, L. Dou. *IEEE Trans. Intell. Trans. Syst 2011*
- Managing power consumption and performance of computing systems using reinforcement learning. [[pdf]](http://papers.nips.cc/paper/3251-managing-power-consumption-and-performance-of-computing-systems-using-reinforcement-learning.pdf)
  - Tesauro, Gerald, et al. *NIPS 2018*

##### W-Learning Approach
- Action selection methods using reinforcement learning. [[pdf]](http://cogprints.org/447/2/g.SAB96.ps)
  - M Humphrys.
##### Analytic Hierarchy Process Approach
- A multi-objective optimization genetic algorithm incorporating preference information. [[pdf]](http://en.cnki.com.cn/Article_en/CJFDTOTAL-XXYK200706016.htm)
  - X Shen, Y Guo, Q Chen, W Hu.
- Multi-objective reinforcement learning algorithm for MOSDMP in unknown environment. [[pdf]](http://en.cnki.com.cn/Article_en/CJFDTOTAL-XXYK200706016.htm)
  - Zhao, Yun, Qingwei Chen, and Weili Hu. *WCICA 2010*
##### Ranking Approach
- Multi-criteria reinforcement learning. [[pdf]](http://www.academia.edu/download/3406069/multi98.ps.pdf)
  - Z Gábor, Z Kalmár, C Szepesvári. *ICML 1998*
- Reinforcement learning with bounded risk. [[pdf]](http://peter-geibel.de/OnlineArticles/icml01.pdf)
  - P Geibel. *ICML 2001*
- Multi-objective reinforcement learning based routing in cognitive radio networks: Walking in a random maze. [[pdf]](http://peter-geibel.de/OnlineArticles/icml01.pdf)
  - K. Zheng, H. Li, RC. Qiu, S. Gong. *ICNC 2012*
##### Geometric Approach
- A geometric approach to multi-criterion reinforcement learning. [[pdf]](http://www.jmlr.org/papers/volume5/mannor04a/mannor04a.pdf)
  - S. Mannor, N. Shimkin. *JMLR 2014*
- The steering approach for multi-criteria reinforcement learning. [[pdf]](http://papers.nips.cc/paper/1986-the-steering-approach-for-multi-criteria-reinforcement-learning.pdf)
  - S. Mannor, N. Shimkin. *NIPS 2002*
  
#### Multiple Policy
##### Convex Hull Approach
- Learning all optimal policies with multiple criteria. [[pdf]](http://www1.icsi.berkeley.edu/~snarayan/icml.pdf)
  - Barrett, Leon, and Srini Narayanan. *ICML 2008*
##### Varying Parameter Approach
- Importance sampling for reinforcement learning with multiple objectives. [[pdf]](https://dspace.mit.edu/bitstream/handle/1721.1/5568/AITR-2001-003.pdf?sequence=2)
  - CR Shelton.

<!---
#### FQI(fitted Q-iteration) Extension

### TBC
- Tree-based fitted q-iteration for multi-objective markov decision problems. [[pdf]](https://re.public.polimi.it/bitstream/11311/690408/1/06252759.pdf)
  - A. Castelletti, F. Pianosi, M. Restelli. *IJCNN 2012*

- Multi-objective optimization by reinforcement learning (Store in elite list)

- Solving multi-objective reinforcement learning problems by EDA-RL-acquisition of various strategies (SP:Estimation of distribution)

- Multi-criteria reinforcement learning based on goal-directed exploration and its application to bipedal walking robot(SP:α-domination strategy+goal-directed bias)

- Multi-objective reinforcement learning algo-rithm and its improved convergency method(SP:parallel genetic algo+perturbation stochastic approximation)

- Parallel reinforcement learn-ing for weighted multi-criteria model with adaptive margin(SP:Adaptive margin)

- Multiobjective reinforcement learning based on multiple value functions(SP:Actor critic)

- Multi-objective fitted Q-iteration: Pareto frontier approximation in one single run(SP:FQI angain:))

- Computing optimal stationary policies for multi-objective Markov decision processes(SP:CON-MODP value iter algo)

- Policy gradient approaches for multi-objective sequential decision making

- Model-based multi-objective reinforcement learning

- Hypervolume-based multi-objective reinforcement learning

- Multi-objective reinforcement learning using sets of pareto dominating policies

- Scalarized Multi-Objective Reinforcement Learning: Novel Design Techniques

- Many-objective stochastic path finding using reinforcement learning

- Multi-objective reinforcement learning through continuous pareto manifold approximation

- Softmax exploration strategies for multiobjective reinforcement learning

-->

### Evolutionary Algorithms
#### Survey
- Multiobjective evolutionary algorithms: A survey of the state of the art [[pdf]](https://dl.acm.org/ft_gateway.cfm?ftid=1627892&id=2792984)
  - Zhou, Aimin, et al.
- Many-Objective Evolutionary Algorithms: A Survey [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.465.9199&rep=rep1&type=pdf)
  - B Li, J Li, K Tang, X Yao. *CSUR 2015*
#### Dominance Based
- A fast and elitist multiobjective genetic algorithm: NSGA-II [[pdf]](https://ieeexplore.ieee.org/document/996017/) [[Official]](https://www.iitk.ac.in/kangal/codes.shtml) [[python]](https://github.com/haris989/NSGA-II) [[C++]](https://github.com/dojeda/nsga2-cpp) [[Java]](https://github.com/onclave/NSGA-II)
  - K. Deb, A. Pratap, S. Agarwal, T. Meyarivan. *IEEE Transactions on Evolutionary Computation 2012*
- SPEA2: Improving the Strength Pareto Evolutionary Algorithm [[pdf]](https://pdfs.semanticscholar.org/6672/8d01f9ebd0446ab346a855a44d2b138fd82d.pdf) [[official]](http://www.cleveralgorithms.com/nature-inspired/evolution/spea.html)
  - E. Zitzler, M. Laumanns, L. Thiele. *TIK-report 2001*
- ISPEA: improvement for the strength Pareto evolutionary algorithm for multiobjective optimization with immunity [[pdf]](https://ieeexplore.ieee.org/abstract/document/1238153/)
  - M. Hongyun, L. Sanyang. *ICCIMA 2003*
- Applications of Vector Evaluated Genetic Algorithms (VEGA) in Ultimate Limit State Based Ship Structural Design [[pdf]](http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=1911976)
  - O. Hughes, M. Ma, JK. Paik. *ASME 2014*
- Shift-based density estimation for Pareto-based algorithms in many-objective optimization [[pdf]](https://bura.brunel.ac.uk/bitstream/2438/12061/1/Fulltext.pdf)
  - M Li, S Yang, X Liu. *IEEE Transactions on Evolutionary Computation 2014*
- The Pareto archived evolution strategy: a new baseline algorithm for Pareto multiobjective optimisation (PAES) [[pdf]](https://ieeexplore.ieee.org/document/781913/)
  - Knowles, Joshua, and David Corne. *CEC 1999*

#### Aggregation Based
- MOEA/D: A multiobjective evolutionary algorithm based on decomposition [[pdf]](http://web.xidian.edu.cn/xlwang/files/20150312_174546.pdf) [[R]](https://github.com/fcampelo/MOEADr) [[python]](https://github.com/mbelmadani/moead-py) [[java]](https://github.com/jMetal/jMetal/blob/master/jmetal-algorithm/src/main/java/org/uma/jmetal/algorithm/multiobjective/moead/MOEAD.java)
  - Q Zhang, H Li. *IEEE Transactions on Evolutionary Computation 2007*
- Normal-boundary intersection: A new method for generating the pareto surface in nonlinear multicriteria optimization problems [[pdf]](https://scholarship.rice.edu/bitstream/handle/1911/101880/TR96-19.pdf?sequence=1)
  - I Das, JE Dennis. *SIAM Journal on Optimization  1998*
- Many-objective directed evolutionary line search [[pdf]](http://www.whitehorseradar.co.uk/PublicationsUPDAT/conf_2011_GECCO_models.pdf)
  - Hughes, E. James. *GECCO 2011*
- Ranking methods for many-objective optimization [[pdf]](http://delta.cs.cinvestav.mx/~ccoello/EMOO/fabre09.pdf.gz)
  - M. Garza-Fabre, GT Pulido, CAC Coello. *MICAI 2009*
- A decomposition based evolutionary algorithm for many objective optimization with systematic sampling and adaptive epsilon control [[pdf]](https://pdfs.semanticscholar.org/8f71/35ba677fa47371688b3b1b77a18b1137c3ad.pdf)
  - Asafuddoula, Md, Tapabrata Ray, and Ruhul Sarker. *EMO 2013*
- Ranking-dominance and many-objective optimization [[pdf]](https://www.researchgate.net/profile/J_Lampinen/publication/224301953_Ranking-Dominance_and_Many-Objective_Optimization/links/0912f509b37511a19c000000/Ranking-Dominance-and-Many-Objective-Optimization.pdf)
  - Kukkonen, Saku, and Jouni Lampinen. *CEC 2017*

#### Indicator Based
- HypE: An algorithm for fast hypervolume-based many-objective optimization [[pdf]](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/12187/1/eth-30945-01.pdf)
  - J. Bader, E. Zitzler.
- An EMO algorithm using the hypervolume measure as selection criterion [[pdf]](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/12187/1/eth-30945-01.pdf)
  - M. Emmerich, N. Beume, B. Naujoks. *EMO 2015*
- Approximation-guided evolutionary multi-objective optimization. [[pdf]](http://www.aaai.org/ocs/index.php/IJCAI/IJCAI11/paper/viewFile/2929/3419)
  - Bringmann, Karl, et al. *IJCAI 2011*
- On the properties of the R2 indicator. [[pdf]](https://hal.archives-ouvertes.fr/docs/00/72/20/60/PDF/pap486s1-brockhoffAuthorVersion.pdf)
  - Brockhoff, Dimo, T. Wagner, and H. Trautmann. *GECCO 2012*
- MOMBI: A new metaheuristic for many-objective optimization based on the R2 indicator. [[pdf]](http://delta.cs.cinvestav.mx/~ccoello/EMOO/hernandez13.pdf.gz)
  - Gómez, Raquel Hernández, and Carlos A. Coello Coello.  *CEC 2013*
- A ranking method based on the R2 indicator for many-objective optimization. [[pdf]](https://www.cs.cinvestav.mx/~EVOCINV/publications/2013/conferences/cec2013-alan-final.pdf.gz)
  - Díaz-Manríquez, Alan, et al.  *CEC 2013*


### Bradient Based
### Others

## License

[![PDM](https://licensebuttons.net/p/mark/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Anjie Zheng](http://anjie.me/) has waived all copyright and related or neighboring rights to this work.

