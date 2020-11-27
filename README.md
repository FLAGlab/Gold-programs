# Gold


This repository contains examples of machines built using Gold

1. Automata
  - [Deterministic Finite Automata][DFA]
  - Nondeterministic Finite Automata
  - [Finite State Transducers][FST]
  - [Pushdown Automata][PDA]
2. [Turing machines][TMs]


# Petri nets
The example Petri net programs bellow are defined using both the HiPS : Hierarchical Petri net Simulator<https://sourceforge.net/projects/hips-tools/> using the `.hps` files (for windows users), and Hybrid Petri Net ICSI Simulator<https://sourceforge.net/projects/hisim/> using the `.xml` files (java based simulator).


| Problem Name | Description | Invariant |
| :------------ | :----------- | :--------- |
| [Count][count] | Simulates a counter from 0 to 999 | `CountIn = Temp + p0 + 10*p1 + 100*p2` |
| [Traffic lights][traffic] | Simulates a standard 4-color traffic light | `red + yellow + green <= 2`<br> `red<=1`<br>`yellow<=1`<br>`green<=1` |
| [Basic one queue one processor][1q1p] | One queue serviced by two different processors | `Working1+ReadyProc1=1` <br> `Working2+ReadyProc2=1` |
| [1q2p][1q2p] | One queue serviced by two different processors | `Working1+ReadyProc1=1` <br> `Working2+ReadyProc2=1` |


[DFA]:https://github.com/FLAGlab/Gold-programs/tree/master/DFAs
[FST]:https://github.com/FLAGlab/Gold-programs/tree/master/Transducers
[PDA]: https://github.com/FLAGlab/Gold-programs/tree/master/PDA
[TMs]:https://github.com/FLAGlab/Gold-programs/tree/master/TuringMachines
[1q1p]:https://github.com/FLAGlab/Gold-programs/blob/master/Petri%20nets/1q1p
[1q2p]:https://github.com/FLAGlab/Gold-programs/blob/master/Petri%20nets/1q2p
[traffic]:https://github.com/FLAGlab/Gold-programs/blob/master/Petri%20nets/trafficLight
[count]:https://github.com/FLAGlab/Gold-programs/blob/master/Petri%20nets/Count
