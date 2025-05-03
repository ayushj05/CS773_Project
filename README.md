# CS773 Project: Dynamic Subcache Sizing in HybCache

Tracefiles can be downloaded from [here](https://drive.google.com/drive/folders/1tG-oFIsxFza3GYPzUsMvj_vmLYvQeEcL?usp=sharing).

**Note:** Update the location of tracefiles in `run_2core.sh`.

## To Build
```
./build_champsim.sh bimodal no no no no lru 2
```

## To Run
```
./run_2core.sh bin/bimodal-no-no-no-no-lru-2core 1 2
```

# References
* Ghada Dessouky, Tommaso Frassetto, and Ahmad-Reza Sadeghi. 2020. HYBCACHE: hybrid side-channel-resilient caches for trusted execution environments. In Proceedings of the 29th USENIX Conference on
Security Symposium (SEC'20). USENIX Association, USA, Article 26, 451–468.
* ChampSim simulator was used for this project. Link to their project: https://github.com/ChampSim/ChampSim

## Contributors
* Ayush Joshi, 210100036
* Scaria Kochidanadu, 210020122