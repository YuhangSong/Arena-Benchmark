# Arena-Benchmark



## Common Naming Rules

A typical Arena game will be named like this: ```Arena-Tennis-Sparse-2T1P-Discrete```, which follows some common naming rules as follows:

* ```Arena```: (compulsory) a prefix identifying an Arena environment.
* ```Tennis```: (compulsory) this is the name of the base game, you will see lot of different base games as well as their videos/descriptions in the following [Benchmark](#Benchmark).
* ```aXb```: (optional) the size of the playground is ```a``` times ```b```.
* ```PT```: (optional) penalize tie, if two competitive agents/teams tie the game, both of them will be penalized by a reward of -1.
* ```Sparse/Dense```: (optional) the reward is sparse/dense, the reward is only returned at the end of the episode / every step.
* ```xTyP```: (compulsory) ```x``` teams competiting with each other, and there are ```y``` players in each team.
* ```Discrete/Continuous```: (compulsory) discrete/continuous action space.

The file name of a game will is with an additional suffix, indicating the target platform of the built game.
* ```Linux/Darwin```: (compulsory) the game is built for Linux/Darwin(i.e., Mac).
For example, the file name of above game ```Arena-Tennis-Sparse-2T1P-Discrete``` would be ```Arena-Tennis-Sparse-2T1P-Discrete-Linux``` if it is built for Linux machines.

## Benchmark

- ```Arena```
  - ```Tennis```: [[Video]](xxx) in this game, xxx.
    - ```Sparse```
      - ```2T1P```
        - ```Discrete```
