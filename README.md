# FairNormalization

The code for the paper entitled [**Equitable Artificial Intelligence for Glaucoma Screening with Fair Identity Normalization**](https://www.medrxiv.org/content/10.1101/2023.12.13.23299931v1.full.pdf). If you have any questions, please email <harvardophai@gmail.com> and <harvardairobotics@gmail.com>.

<img src="fig/framework.png" width="600">

# Requirements

To install the prerequisites, run:

```
pip install - r requirements.txt
```

# Experiments

To run the experiments with the baseline models on 2D RNFLT maps, execute:
```
./scripts/train_glaucoma_fair_npj.sh
```

To run the experiments with the baseline models with the proposed FIN module on 3D OCT B-scans, execute:
```
./scripts/train_glaucoma_fair_proposed_npj.sh
```

## Acknowledgement and Citation

If you find this repository useful for your research, please consider citing our [paper](https://www.medrxiv.org/content/10.1101/2023.12.13.23299931v1.full.pdf):

```bibtex
@article{shi2025equitable,
  title={Equitable artificial intelligence for glaucoma screening with fair identity normalization},
  author={Shi, Min and Luo, Yan and Tian, Yu and Shen, Lucy Q and Zebardast, Nazlee and Eslami, Mohammad and Kazeminasab, Saber and Boland, Michael V and Friedman, David S and Pasquale, Louis R and others},
  journal={NPJ Digital Medicine},
  volume={8},
  number={1},
  pages={46},
  year={2025},
  publisher={Nature Publishing Group UK London}
}
```


# Licence

Apache License 2.0

