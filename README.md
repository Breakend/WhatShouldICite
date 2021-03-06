# WhatShouldICite
This is an informal record of original citations that I'm aware of for key terms in scientific literature. It started because I didn't know what's the original work to cite for eligibility traces and it seems important to do proper credit assignment.

## UCB

Seems like confidence in the face of uncertainty is here:

```
@article{lai1985asymptotically,
  title={Asymptotically efficient adaptive allocation rules},
  author={Lai, Tze Leung and Robbins, Herbert},
  journal={Advances in applied mathematics},
  volume={6},
  number={1},
  pages={4--22},
  year={1985},
  publisher={Academic Press}
}
```

Then versions of UCB popular in bandit literature are in these two:

```

@article{auer2002finite,
  title={Finite-time analysis of the multiarmed bandit problem},
  author={Auer, Peter and Cesa-Bianchi, Nicolo and Fischer, Paul},
  journal={Machine learning},
  volume={47},
  number={2-3},
  pages={235--256},
  year={2002},
  publisher={Springer}
}

@inproceedings{kocsis2006bandit,
  title={Bandit based monte-carlo planning},
  author={Kocsis, Levente and Szepesv{\'a}ri, Csaba},
  booktitle={European conference on machine learning},
  pages={282--293},
  year={2006},
  organization={Springer}
}

```

## Likelihood Ratio

This is an interesting one, I had to dig it up and it's not available for finding easily online. 

```
@article{aleksandrov1968stochastic,
  title={Stochastic optimization},
  author={Aleksandrov, VM and Sysoyev, VI and SHEMENEV. VV},
  journal={Engineering Cybernetics},
  number={5},
  pages={11--+},
  year={1968}
}

```


## Eligibility traces

Based on stimulus traces by Hull and memory traces by Klopf, the earliest work that I could find on this is that of Sutton and Barto. Probably best to cite Klopf, Sutton, and Barto.

```
@article{sutton1981toward,
  title={Toward a modern theory of adaptive networks: expectation and prediction.},
  author={Sutton, Richard S and Barto, Andrew G},
  journal={Psychological review},
  volume={88},
  number={2},
  pages={135},
  year={1981},
  publisher={American Psychological Association}
}

@techreport{klopf1972brain,
  title={Brain function and adaptive systems: a heterostatic theory},
  author={Klopf, A Harry},
  year={1972},
  institution={AIR FORCE CAMBRIDGE RESEARCH LABS HANSCOM AFB MA}
}

```

## REINFORCE

If citing this, should likely also cite Aleksandrov for the likelihood ratio which looks essentially like REINFORCE, see Eq. 2.5 of aleksandrov1968stochastic.

```
@inproceedings{williams1987class,
  title={A class of gradient-estimation algorithms for reinforcement learning in neural networks},
  author={Williams, R},
  booktitle={Proceedings of the International Conference on Neural Networks},
  pages={II--601},
  year={1987}
}

@article{williams1992simple,
  title={Simple statistical gradient-following algorithms for connectionist reinforcement learning},
  author={Williams, Ronald J},
  journal={Machine learning},
  volume={8},
  number={3-4},
  pages={229--256},
  year={1992},
  publisher={Springer}
}
```

## Policy gradient

This is essentially REINFORCE with value functions, if using purely Monte carlo, should probably cite REINFORCE (but should probably cite all three for policy gradient anyways?).
```
@inproceedings{sutton2000policy,
  title={Policy gradient methods for reinforcement learning with function approximation},
  author={Sutton, Richard S and McAllester, David A and Singh, Satinder P and Mansour, Yishay},
  booktitle={Advances in neural information processing systems},
  pages={1057--1063},
  year={2000}
}
```

## TD(λ)

```
@article{sutton1988learning,
  title={Learning to predict by the methods of temporal differences},
  author={Sutton, Richard S},
  journal={Machine learning},
  volume={3},
  number={1},
  pages={9--44},
  year={1988},
  publisher={Springer}
}
```

