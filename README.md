# Unsupervised Estimation of Nonlinear Audio Effects: Comparing Diffusion-Based and Adversarial approaches

This is the official supplementary repository for the paper.

#### [webpage 🎶](https://michalsvento.github.io/UnNAFx/) |  [paper 📰](https://arxiv.org/abs/2504.04751)


## Abstract


Accurately estimating nonlinear audio effects without access to paired input-output signals remains a challenging problem.
This work studies unsupervised probabilistic approaches for solving this task. We introduce a method, novel for this application, based on diffusion generative models for blind system identification, enabling the estimation of unknown nonlinear effects using black- and gray-box models.
This study compares this method with a previously proposed adversarial approach, analyzing the performance of both methods under different parameterizations of the effect operator and varying lengths of available effected recordings.
Through experiments on guitar distortion effects, we show that the diffusion-based approach provides more stable results and is less sensitive to data availability, while the adversarial approach is superior at estimating more pronounced distortion effects.
Our findings contribute to the robust unsupervised blind estimation of audio effects, demonstrating the potential of diffusion models for system identification in music technology.


## Code

To be published...

## Citing

If you find this code useful in your research, please consider citing:

```
@article{moliner2025UnNAFx,
      title={Unsupervised Estimation of Nonlinear Audio Effects: Comparing Diffusion-Based and Adversarial approaches}, 
      author={Eloi Moliner and Michal Švento and Alec Wright and Lauri Juvela and Pavel Rajmic and Vesa Välimäki},
      year={2025},
      eprint={2504.04751},
      url={https://arxiv.org/abs/2504.04751}, 
}
```