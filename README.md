# Arena-Benchmark



## Common Naming 

A typical Arena game will be named like this: ```Arena-Tennis-Sparse-2T1P-Discrete```, which follows some common naming rules as follows:

* ```Arena```: a prefix identifying an Arena environment.
* ```Sparese```: the reward is sparse, the reward is only returned at the end of the episode.
* ```Dense```: the reward is dense, the reward is returned every step.
* ```xTyP```: ```x``` teams competiting with each other, and there are ```y``` players in each team.
* ```Discrete```: discrete action space.
* ```Continues```: continues action space.
* ```aXb```: the size of the playground is ```a``` times ```b```.
* ```PT```: penalize tie, if two competitive agents/teams tie the game, both of them will be penalized by a reward of -1.

## Benchmark

- ```Arena```
  - ```Tennis```
    - ```Sparse```
      - ```2T1P```
        - ```Discrete```
