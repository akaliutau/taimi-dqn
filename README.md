# About

This is the coding part of the project ELEC70121 Trustworthy Artificial Intelligence in Medical Imaging.

# Abstract

This work presents a novel Deep Reinforcement Learning
approach for optimizing k-space vertical line selection in undersampled
Magnetic Resonance Imaging (MRI). By training a Deep Q-Network
(DQN) agent to directly learn a sampling policy from reconstruction
quality feedback (PSNR and SSIM), we demonstrate its ability to dis-
cover strategies superior to common heuristics, especially in high uncer-
tainty regimes. Experimental results demonstrate significant quantitative
gains, suggesting that actively tailoring sampling patterns to specific im-
age content and the reconstruction process through RL can substantially
improve accelerated MRI performance within a fixed acquisition budget.
This work highlights the potential of reinforcement learning for precise
image reconstruction within the MRI workflow, opening promising av-
enues for further improvement of clinical MRI technologies.

# Cite

If you use code or ideas, please cite this repository

```
@misc{kaliutau2025mri,
  title={Deep {Q-Networks} in Adaptive k-space Sampling for Precision {MRI}},
  author={Kaliutau, Aliaksei},
  publisher = {GitHub},
  journal = {GitHub repository},
  url = {https://github.com/akaliutau/taimi-dqn}
  year={2025}
}
```

# References

[1]. https://github.com/facebookresearch/fastMRI 


