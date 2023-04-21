## Actor-Sharer-Learner (ASL): An Efficient Training Framework for Off-policy Deep Reinforcement Learning
<div align="center">
  <a ><img width="1200px" height="auto" src="https://github.com/XinJingHao/Images/blob/main/asl/ASL.jpg"></a>
</div>

![Python](https://img.shields.io/badge/Python-blue)
![DRL](https://img.shields.io/badge/DRL-blueviolet)
![TrainingFramework](https://img.shields.io/badge/TrainingFramework-ff69b4)

## Preface
This is the code of the ASL framework in paper [Color:train](xxxx). In addition, the Sparrow simulator can be found [here](https://github.com/XinJingHao/Sparrow-V0).

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
@misc{Sparrow_v0,
  author = {Jinghao Xin},
  title = {XXXXXXXXXXX},
  year = {2023},
  publisher = {XXXX},
  journal = {XXX},
  howpublished = {XXXX},
}
```
