# SDE Matching

We present SDE Matching, a new simulation-free method for training Latent Stochastic Differential Equations (Latnet SDEs).
The Latent SDE is a powerful tool for time series and sequence modeling.
However, training Latent SDEs typically relies on adjoint sensitivity methods, which depend on simulation and backpropagation through approximate SDE solutions, which limit scalability.
Inspired by modern Score- and Flow Matching algorithms for learning generative dynamics, we extend these ideas to the domain of stochastic dynamics for time series and sequence modeling, eliminating the need for costly numerical simulations.

Check out the [paper](https://arxiv.org/abs/2502.02472) for more details.

## Setup

We provide a `requirements.txt` file for a pip environment. 

```bash
pip install -r requirements.txt
```

## Getting started

The best way to understand SDE Matching is to look at [the notebook](https://github.com/GrigoryBartosh/sde_matching/blob/main/sde_matching_from_scratch.ipynb) which contains a simple implementation of the SDE Matching on 3D stochastic Lorenz attractor data.

## Citation

If you find our work useful, please consider citing our paper:

```bibtex
@article{bartosh2024sde,
  title={SDE Matching: Scalable and Simulation-Free Training of Latent Stochastic Differential Equations},
  author={Bartosh, Grigory and Vetrov, Dmitry P and Andersson Naesseth, Christian},
  journal={The 43st International Conference on Machine Learning (ICML)},
  year={2025}
}
```