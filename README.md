## Actor-Sharer-Learner (ASL): An Efficient Training Framework for Off-policy Deep Reinforcement Learning
<div align="center">
  <a ><img width="1200px" height="auto" src="https://github.com/XinJingHao/Images/blob/main/asl/ASL.jpg"></a>
</div>

![Python](https://img.shields.io/badge/Python-blue)
![DRL](https://img.shields.io/badge/DRL-blueviolet)
![TrainingFramework](https://img.shields.io/badge/TrainingFramework-ff69b4)

## Dependencies
```bash
envpool >= 0.6.6  (https://envpool.readthedocs.io/en/latest/)
torch >= 1.13.0  (https://pytorch.org/)
numpy >= 1.23.4  (https://numpy.org/)
tensorboard >= 2.11.0  (https://pytorch.org/docs/stable/tensorboard.html)
python >= 3.8.0 
ubuntu >= 18.04.1 
```

## Quick Start:
After installation, you can use the ASL framework to train an Atari agent via:
```bash
python main.py
```
where the default envionment is **Alien** and the underlying DRL algorithm is **DDQN**. For more details about experiment setup, please check the **main.py**. The trianing curves of 57 Atari games are listed as follows.

<div align="center">
<img width="100%" height="auto" src="https://github.com/XinJingHao/Images/blob/main/asl/ss_e.svg">
</div>


## Citing the Project

To cite this repository in publications:

```bibtex
@article{Color2023JinghaoXin,
  title={Train a Real-world Local Path Planner in One Hour via Partially Decoupled Reinforcement Learning and Vectorized Diversity},
  author={Jinghao Xin, Jinwoo Kim, Zhi Li, and Ning Li},
  journal={arXiv preprint arXiv:2305.04180},
  url={https://doi.org/10.48550/arXiv.2305.04180},
  year={2023}
}
```
